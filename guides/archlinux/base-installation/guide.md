# Installing Archlinux manually

Flashing Archlinux ISO, the first thing you want to do is install the ISO from
'https://fastly.mirror.pkgbuild.com/iso/2026.10.01/'.
Install the one that says .iso located at the top and sha256sums.txt located at the bottom.

Then make sure the sums are correct, if they arent reinstall it but if it is then you can start flashing it by plugging in your USB into the USB port of your PC.

Then install Ventoy, open the app then install it onto your USB that you have plugged into your computer. Then move the archiso to the USB or copy it to the USB.

 Once you have finished those steps, boot into your firmware interface by repetitively pressing f12 right after rebooting. Then once you are in the firmware interface disable Secure Boot because first of all its shitty and second you wont be able to boot into the archiso without a key, then you find your USB device with the archiso on it then click it. You will be in archiso, run 'sgdisk --zap-all /dev/nvme0n1' which will wipe everything off like obliterate it, then run 'reboot' and repetively press f12 to get into the firmware interface once again. Then click your USB again then you will be inside the archiso

 Once you are in run 'ping -c 4 1.1.1.1' if it doesnt return any packets that means you arent using ethernet so get an ethernet cable, plug it into the router then to your pc. If you do not have one run these commands in sequence 'iwctl', 'device list', 'station wlan0 scan', 'station wlan0 get-networks', 'station wlan0 connect "your-wifi-name", 'exit'.

 Then set your system system clock. Run 'timedatectl set-ntp true' then you need to partition your drive, run 'lsblk' and identify your drive. Assuming your drive is named 'nvme0n1' run 'cfdisk /dev/nvme0n1' then it asks for the drive label, choose GPT then make your first drive navigate to new with your arrow keys and then set the partition size to '+1G' or '1G' then navigate to type and hit enter, use your arrow keys again to navigate up and set it to 'EFI System' then go back and make another partition but this time make it the default size it says then after that navigate to write with your arrow keys then it will prompt you enter 'yes' not 'y'.

 Once you have finished, format your partitions. run 'mkfs.fat -F32 /dev/nvme0n1p1' and 'mkfs.btrfs -f /dev/nvme0n1p2'. Then create the BTRFS subvolumes by running 'mount /dev/nvme0n1p2 /mnt', 'btrfs subvolume create /mnt/@', 'btrfs subvolume create /mnt/@home', 'btrfs subvolume create /mnt/@snapshots' (snapshots are optional) then run 'umount /mnt' and run 'mount -o noatime,compress=zstd,subvol=@ /dev/nvme0n1p2 /mnt' then create the necessary directories by running 'mkdir -p /mnt/{boot,home,.snapshots}' and then run 'mount -o noatime,compress=zstd,subvol=@home /dev/nvme0n1p2 /mnt/home' and run 'mount -o noatime,compress=zstd,subvol=@snapshots /dev/nvme0n1p2 /mnt/.snapshots' and lastly run 'mount /dev/nvme0n1p1 /mnt/boot'

 Once you have finished all of that mounting bullshit, install the base system by running 'pacstrap -K /mnt base linux linux-firmware btrfs-progs networkmanager sudo nano grub efibootmgr'.

And once you have finished installing the base system, generate the filesystem table but running 'genfstab -U /mnt >> /mnt/etc/fstab' then run 'arch-chroot /mnt' and configure your timezone by running 'ln -sf /usr/share/zoneinfo/Your/Timezone /etc/localtime' and run 'hwclock --systohc'. Run 'nano /etc/locale.gen' and uncomment "en_US.UTF-8 UTF-8" or whatever locale you choose. Generate your locale by running 'locale-gen' and select your language by running 'echo "LANG=en_US.UTF-8" > /etc/locale.conf' and select your hostname by running 'echo "archlinux" > /etc/hostname'. Then run 'nano /etc/hosts' and add 

"
127.0.0.1 localhost
::1 localhost
127.0.1.1 archlinux.localdomain archlinux
"

Then run 'passwd' to set your root password and run 'useradd -m -G wheel -s /bin/bash <your-username>' and run 'passwd <your-username> and run 'EDITOR=nano visudo' and uncomment "%wheel ALL=(ALL:ALL) ALL" and run 'systemctl enable NetworkManager' and run 'grub-install --target=x86_64-efi --efi-directory=/boot --bootloader-id=GRUB' thenr run 'grub-mkconfig - o /boot/grub/grub.cfg' and then once it finished without error run 'exit' and run 'umount -R /mnt' then reboot, your PC should show the grub menu which will automatically boot after 3 seconds by default. Then remove your USB and you are done.

