# Installing Archlinux manually
This guide covers installing the base Arch Linux system.

⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠉⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠃⠀⠈⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣿⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣽⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⣿⣿⣿⣿⣹⣿⣿⣿⣿⣿⣿⠏⠀⠀⠀⠘⣿⣿⣟⣿⣿⣿⣯⣿⣿⣿⣿⣿⣿⣿⣽⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣏⣿⣿⣿⣿
⣿⣿⣿⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣟⣿⣿⡿⣿⣞⣻⣿⢻⣿⣿⣛⣻⣿⡟⠀⠀⠀⠀⠀⠹⣿⡟⣛⣾⣿⣟⣿⣟⣳⣿⣾⣿⣿⢻⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⡟⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣿⣿⣿⡿⠀⠀⠀⠀⠀⠀⠀⢹⣿⣿⣻⣿⣿⣿⣿⣟⣿⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣿⣿⣷⣿⣿⣿⣿
⣿⣿⣿⣿⣸⣿⣿⣿⣿⣿⣿⣯⣿⣿⣿⣿⣿⣿⣯⣿⢿⡿⣿⣼⣿⡿⣿⡿⠁⠀⠀⠀⠀⠀⠀⠀⠀⢳⣿⢿⣿⣇⣿⣿⡿⣿⣿⣿⣿⣽⣿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣧⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣿⣿⢻⣿⣿⡿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢻⣾⣿⡿⣿⣿⣷⣿⣾⣿⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣿⣿⣿⣿
⣿⣿⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢿⣿⣿⣾⣿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⢿⣿⢿⣿⣟⣿⣹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣼⣿⣿⣿⣿⣿⣿⣇⣿⣿⣿⣧⣿⣿⣟⣿⣿⣿⣿⣸⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣿⣇⣿⣿⣿⣿⣿⣿⣿⣼⣿⣿⣿⣼⣿⣿⣿⣿⣿⣿⣇⣿⣿⣿⣿
⣿⣿⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣾⣿⣿⢻⣏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⡟⣿⣿⣧⣿⣾⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⡟⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣿⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⣿⡌⢿⣷⣤⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⣿⣟⣿⢻⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⡟⣿⣿⣷⣿⣿⣿⣿
⣿⣿⣿⣿⣸⣿⣿⢿⣿⣿⣿⢯⣿⣿⢿⣿⢿⣿⣯⣿⢿⣿⡟⠀⠀⠈⠛⢿⣤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⡿⣿⢿⣿⡿⣹⣿⣿⣿⡿⣿⣿⣿⡿⣿⣿⣇⣿⣿⣿⣿
⣿⣿⣿⣿⢿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣿⣿⣿⣿⡟⣿⣾⡟⠀⠀⠀⠀⠀⠀⠈⠙⠲⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣷⣿⣾⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⡟⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⣷⣿⣿⣿⣷⣿⣿⣷⡟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⣾⣿⣿⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⣿⣿⣿⣿
⣿⣿⣿⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣿⣿⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣿⣿⣿⣿
⣿⣿⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⡟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⢿⣿⣿⣿⣿⣿⣿⣿⣏⣿⣿⡿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⣿⣿⠏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⣿⣿
⣿⣿⣿⣿⢻⣿⣿⣿⣿⣿⣿⣟⣿⣿⣿⠏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣿⣿⣿⣿
⣿⣿⣿⣿⢿⣿⣿⣿⣿⣿⣿⡿⣿⣿⠏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣴⣶⣶⣶⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣟⣿⢿⣿⣿⣿⣧⣿⣿⡿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣾⣿⣼⣿⣿⣻⣿⣿⣷⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⣿⣿⣿⣿⣿⡿⣿⣿⣷⣿⣿⣿⣿
⣿⣿⣿⣿⣹⣿⣿⣿⣿⣿⣿⣿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣿⣶⣿⣹⣿⣿⣿⣿⣿⣿⡿⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢷⣾⣿⣿⣿⣿⣿⣏⣿⣿⣿⣿
⣿⣿⣿⣿⢻⣿⣿⣾⣷⣿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣾⣻⣿⣿⢿⣿⣿⣾⣿⣿⣿⡟⣷⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⣻⣿⣧⣿⣿⡟⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣽⡿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠅⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⣽⡟⣿⣿⣷⣿⣿⣿⣿
⣿⣿⣿⣿⢹⣿⣿⣿⣿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣽⣿⣿⣿⣿⣿⣿⡟⣿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⣶⣤⣤⠀⠈⢻⣿⣿⣿⣯⣿⣿⣿⣿
⣿⣿⣿⣿⢿⣿⢿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⠿⢷⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣔⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠛⣷⣶⣌⣃⡿⣿⡿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠻⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⠻⣟⣿⣿⣷⣿⣿⣿⣿
⣿⣿⣿⣿⣹⡾⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⢀⣀⣤⣴⣿⣿⣿⣿⣻⣿⣿⣿⣿⣿⣿⣯⣿⣧⣤⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⢷⣎⣿⣿⣿⣿
⣿⣿⣿⣿⡿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣠⣤⣶⣾⣿⣿⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣼⣿⡿⣿⣿⣷⣶⣤⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢿⣻⣿⣿⣿
⣿⣿⣿⡟⠀⠀⠀⠀⠀⠀⠀⠀⣠⣤⢶⣿⣿⣿⣯⣿⣻⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⣿⣷⣿⣿⣏⣿⢻⣿⣿⣿⣶⣤⣄⠀⠀⠀⠀⠀⠀⠀⠀⢻⣽⣿⣿
⣿⣿⡟⠀⠀⠀⠀⠀⣠⣤⡾⢟⣿⣿⢿⣿⢿⣿⣯⣿⢿⡿⣿⣹⣿⡿⣿⡿⣿⣿⣽⣿⣿⣿⣿⣿⣿⣟⣿⢿⣿⣏⢿⣿⡿⣿⢿⣿⣿⣹⡿⣿⣿⡿⢷⣦⣄⡀⠀⠀⠀⠀⢹⣿⣿
⣿⠏⠀⠀⣠⣴⣾⣿⣯⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣿⣿⢻⣿⣿⣿⣿⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⡿⣿⣿⣷⣿⣾⣿⣿⣻⣿⣿⣿⣿⣿⣿⣿⣯⣷⣤⣄⠀⠀⠹⣿
⢏⣠⣶⣾⣿⣿⣿⣽⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣏⣿⣿⣿⣿⣶⣄⡹

Flashing the Archlinux ISO, the first thing you need to do is get a USB that has atleast 1.5G of storage. Then you need to install Ventoy and install it to the USB and get the Archlinux ISO at https://fastly.mirror.pkgbuild.com/iso/2026.10.01/ and download the ISO.

Then move your Archlinux ISO onto the USB with Ventoy installed on. And after that boot into your firmware interface usually by pressing your F12 key at the top of your keyboard until you get into the Basic Input Output System (BIOS) and disable Secure boot (UEFI) then boot into your USB that shows up. When you boot into it, it will show a terminal which you want to run 

---------------------
lsblk
---------------------

to identify your drive name.

then check your internet connection by running

---------------------
ping -c 3 1.1.1
---------------------

if you are connected automatically you are probably means you are using ethernet, but if it doesnt return any packets then connect to your internet by running

------
nmtui
------

then set your system clock by running
and set your hostname by running 


-----------------
sgdisk --zap-all
-----------------

and repartition your disks by running 

---------------------------------------------------------
cdisk /dev/nvme0n1 # assuming your drive name is nvme0n1
---------------------------------------------------------

set the drive label to GPT then make a new label by selecting new and then entering 1G and make the type EFI System and new another new label which you will leave for cfdisk to set everything by default then select write to write the new partition changes to your drive and enter yes not y or anything else and quit.

You will return to the archiso which you will need to partition your drives (this one shows how to partition your drive in btrfs and ext4 after) by running 

---------------------------------------------------------
mkfs.fat -F32 /dev/nvme0n1p1
---------------------------------------------------------

then format your second partition in BTRFS by running 

---------------------------------------------------------
mkfs.btrfs -f /dev/nvme0n1p2
---------------------------------------------------------

then create the subvolumes by running

---------------------------------------------------------
mount /dev/nvme0n1p2 /mnt
---------------------------------------------------------

then 

---------------------------------------------------------
btrfs subvolume create /mnt/@
---------------------------------------------------------

then

---------------------------------------------------------
btrfs subvolume create /mnt/@home
---------------------------------------------------------

and 

---------------------------------------------------------
btrfs subvolume create /mnt/@snapshots # optional but useful for having system snapshots with like timeshift for snapper
---------------------------------------------------------

then run

---------------------------------------------------------
 mount -o noatime,compress=zstd,subvol=@snapshots /dev/nvme0n1p2 /mnt/.snapshots
---------------------------------------------------------

---------------------------------------------------------
umount /mnt 
---------------------------------------------------------

and run

---------------------------------------------------------
mount -o noatime,compress=zstd,subvol=@ /dev/nvme0n1p2 /mnt
---------------------------------------------------------

after that create the necessary directories by running

---------------------------------------------------------
mkdir -p /mnt/{boot,home,.snapshots}
---------------------------------------------------------

and then run

---------------------------------------------------------
mount -o noatime,compress=zstd,subvol=@home /dev/nvme0n1p2 /mnt/home
---------------------------------------------------------

and 

---------------------------------------------------------
mount -o noatime,compress=zstd,subvol=@snapshots /dev/nvme0n1p2 /mnt/.snapshots
---------------------------------------------------------

then lastly run

---------------------------------------------------------
mount /dev/nvme0n1p1 /mnt/boot
---------------------------------------------------------

Once you have finished mounting and that system commands bullshit, install the base system by running 

---------------------------------------------------------
pacstrap -K /mnt base linux linux-firmware btrfs-progs networkmanager sudo nano grub efibootmgr
---------------------------------------------------------

then generate your filesystem table by running 

---------------------------------------------------------
genfstab -U /mnt >> /mnt/etc/fstab
---------------------------------------------------------

then chroot by running

---------------------------------------------------------
arch-chroot /mnt
---------------------------------------------------------

and then configure your timezone by running

---------------------------------------------------------
ln -sf /usr/share/zoneinfo/your/timezone /etc/localtime
---------------------------------------------------------

then run

---------------------------------------------------------
hwclock --systohc
---------------------------------------------------------

and then set your locale by running

---------------------------------------------------------
nano /etc/locale.gen
---------------------------------------------------------

and in /etc/locale.gen uncomment your desired locale and then save your changes and run

---------------------------------------------------------
locale-gen
---------------------------------------------------------

then run

---------------------------------------------------------
echo "LANG=en_US.UTF-8" > /etc/locale.conf
---------------------------------------------------------

and select your hostname by running

---------------------------------------------------------
echo "archlinux" > /etc/hostname
---------------------------------------------------------

then run 

---------------------------------------------------------
nano /etc/hosts
---------------------------------------------------------

then add 

---------------------------------------------------------
127.0.0.1 localhost
::1 localhost
127.0.1.1 archlinux.localdomain archlinux
---------------------------------------------------------

and then set your root password by running 

---------------------------------------------------------
passwd
---------------------------------------------------------

and to make your user run 

---------------------------------------------------------
useradd -m -G wheel -s /bin/bash <your-username>
---------------------------------------------------------

then to set a password for that account run 

---------------------------------------------------------
passwd <your-username>
---------------------------------------------------------

then run

---------------------------------------------------------
EDITOR=nano visudo
---------------------------------------------------------

and uncomment

---------------------------------------------------------
%wheel ALL=(ALL:ALL) all"
---------------------------------------------------------

and run

---------------------------------------------------------
systemctl enable NetworkManager
---------------------------------------------------------

and to install grub run

---------------------------------------------------------
grub-install --target=x86_64-efi --efi-directory=/boot --bootloader-id=GRUB
---------------------------------------------------------

then run

---------------------------------------------------------
grub-mkconfig -o /boot/grub/grub.cfg
---------------------------------------------------------

and make sure that it shows that it added entries for something like vmzlinux because that means grub found your OS

then run

---------------------------------------------------------
exit
---------------------------------------------------------

and unmount by running

---------------------------------------------------------
umount -R /mnt
---------------------------------------------------------

then run

---------------------------------------------------------
reboot
---------------------------------------------------------

you should boot into the grub menu which boot your os in 3 seonds by default
Then run 'passwd' to set your root password and run 'useradd -m -G wheel -s /bin/bash <your-username>' and run 'passwd <your-username> and run 'EDITOR=nano visudo' and uncomment "%wheel ALL=(ALL:ALL) ALL" and run 'systemctl enable NetworkManager' and run 'grub-install --target=x86_64-efi --efi-directory=/boot --bootloader-id=GRUB' thenr run 'grub-mkconfig - o /boot/grub/grub.cfg' and then once it finished without error run 'exit' and run 'umount -R /mnt' then reboot, your PC should show the grub menu which will automatically boot after 3 seconds by default. Then remove your USB and you are done.

ot because first of all its shitty and second you wont be able to boot into the archiso without a key, then you find your USB device with the archiso on it then click it. You will be in archiso, run 'sgdisk --zap-all /dev/nvme0n1' which will wipe everything off like obliterate it, then run 'reboot' and repetively press f12 to get into the firmware interface once again. Then click your USB again then you will be inside the archiso

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

