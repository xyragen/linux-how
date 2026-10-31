# Guide to Manually Installing Arch Linux

First get a USB with an Arch Linux ISO. You can download the ISO at https://archlinux.org/download/

Then boot into the USB from your firmware interface after plugging it in.

Run this command to identify your storage drive.

```bash
lsblk
````

Then wipe your storage drive, assuming its name is `nvme0n1`.

bash

```bash
sgdisk --zap-all /dev/nvme0n1
```

Now partition your drive by running cfdisk.

bash

```bash
cfdisk /dev/nvme0n1
```

Once you are in cfdisk there should be no partitions, so it will ask what drive label you want. Choose GPT, which is the default.

Then select New and set the size to `+1G` and press enter. Change the partition type to EFI System.

Now create another partition and accept the default size so it uses the remaining space. Make sure its type is Linux filesystem.

Then select Write, confirm, and quit.

## Formatting and mounting with BTRFS

First format the EFI partition as FAT32.

bash

```bash
mkfs.fat -F32 /dev/nvme0n1p1
```

Now format the root partition as BTRFS.

bash

```bash
mkfs.btrfs -f /dev/nvme0n1p2
```

Temporarily mount the root partition.

bash

```bash
mount /dev/nvme0n1p2 /mnt
```

Now create the subvolumes by running these commands.

bash

```bash
btrfs subvolume create /mnt/@
btrfs subvolume create /mnt/@home
btrfs subvolume create /mnt/@snapshots
```

Then unmount the root partition.

bash

```bash
umount /mnt
```

Now mount the root subvolume.

bash

```bash
mount -o noatime,compress=zstd,subvol=@ /dev/nvme0n1p2 /mnt
```

Create the necessary directories.

bash

```bash
mkdir -p /mnt/home
mkdir -p /mnt/.snapshots
mkdir -p /mnt/boot
```

Now mount the home subvolume.

bash

```bash
mount -o noatime,compress=zstd,subvol=@home /dev/nvme0n1p2 /mnt/home
```

Mount the snapshots subvolume.

bash

```bash
mount -o noatime,compress=zstd,subvol=@snapshots /dev/nvme0n1p2 /mnt/.snapshots
```

And lastly mount the EFI partition.

bash

```bash
mount /dev/nvme0n1p1 /mnt/boot
```

## Formatting and mounting with EXT4

First format the EFI partition as FAT32.

bash

```bash
mkfs.fat -F32 /dev/nvme0n1p1
```

Now format the root partition as EXT4.

bash

```bash
mkfs.ext4 -F /dev/nvme0n1p2
```

Mount the root partition.

bash

```bash
mount /dev/nvme0n1p2 /mnt
```

Create the boot directory.

bash

```bash
mkdir -p /mnt/boot
```

And mount the EFI partition.

bash

```bash
mount /dev/nvme0n1p1 /mnt/boot
```

## Connecting to the internet

If you don't have an Ethernet connection, you will need to connect to Wi-Fi.

Run iwctl.

bash

```bash
iwctl
```

Then list your wireless devices.

bash

```bash
device list
```

Scan for available networks, replacing wlan0 with your wireless device name if necessary.

bash

```bash
station wlan0 scan
```

Now list the available networks.

bash

```bash
station wlan0 get-networks
```

Connect to your Wi-Fi network.

bash

```bash
station wlan0 connect YOUR_WIFI_NAME
```

Then exit iwctl.

bash

```bash
exit
```

Check if you are connected by running.

bash

```bash
ping archlinux.org
```

## Installing the base system

Now install the base system by running.

bash

```bash
pacstrap -K /mnt base linux linux-firmware networkmanager sudo nano
```

If you formatted with BTRFS, also install btrfs-progs.

bash

```bash
pacstrap -K /mnt btrfs-progs
```

If you have an Intel CPU, install the Intel microcode.

bash

```bash
pacstrap -K /mnt intel-ucode
```

And if you have an AMD CPU, install the AMD microcode instead.

bash

```bash
pacstrap -K /mnt amd-ucode
```

## Generating fstab

Now generate your fstab by running.

bash

```bash
genfstab -U /mnt >> /mnt/etc/fstab
```

You can check if everything was added correctly by running.

bash

```bash
cat /mnt/etc/fstab
```

Now enter the newly installed system by running.

bash

```bash
arch-chroot /mnt
```

## Configuring the system

First set your timezone by running.

bash

```bash
ln -sf /usr/share/zoneinfo/Region/City /etc/localtime
```

Replace Region/City with your actual timezone.

Now synchronize the hardware clock.

bash

```bash
hwclock --systohc
```

Configure the locale by opening the locale.gen file.

bash

```bash
nano /etc/locale.gen
```

Find `en_US.UTF-8 UTF-8` and uncomment it by removing the # at the beginning.

Save and exit, then generate the locales.

bash

```bash
locale-gen
```

Now set your system's default language.

bash

```bash
echo "LANG=en_US.UTF-8" > /etc/locale.conf
```

Set your hostname.

bash

```bash
echo "archlinux" > /etc/hostname
```

Now open the hosts file.

bash

```bash
nano /etc/hosts
```

Add these lines.

text

```text
127.0.0.1   localhost
::1         localhost
127.0.1.1   archlinux.localdomain archlinux
```

Save and exit.

Now set your root password.

bash

```bash
passwd
```

Create your user by running the following command, replacing yourusername with your preferred username.

bash

```bash
useradd -m -G wheel yourusername
```

Now set your user's password.

bash

```bash
passwd yourusername
```

Allow users in the wheel group to use sudo by running.

bash

```bash
EDITOR=nano visudo
```

Find this line and uncomment it.

text

```text
%wheel ALL=(ALL:ALL) ALL
```

Save and exit.

## Installing and configuring the bootloader

For this guide we will use systemd-boot.

First install the bootloader.

bash

```bash
bootctl install
```

Now configure the bootloader by running.

bash

```bash
nano /boot/loader/loader.conf
```

Add these lines.

text

```text
default arch.conf
timeout 3
console-mode max
editor no
```

Save and exit.

Now find your root partition UUID by running.

bash

```bash
blkid -s UUID -o value /dev/nvme0n1p2
```

Copy the UUID returned by the command.

Now create a boot entry.

bash

```bash
nano /boot/loader/entries/arch.conf
```

If you formatted with BTRFS, add these lines and replace YOUR-UUID with your actual UUID.

text

```text
title Arch Linux
linux /vmlinuz-linux
initrd /initramfs-linux.img
options root=UUID=YOUR-UUID rootflags=subvol=@ rw
```

If you formatted with EXT4, use this instead.

text

```text
title Arch Linux
linux /vmlinuz-linux
initrd /initramfs-linux.img
options root=UUID=YOUR-UUID rw
```

If you installed Intel microcode, add this line above the initramfs line.

text

```text
initrd /intel-ucode.img
```

If you installed AMD microcode, add this line instead.

text

```text
initrd /amd-ucode.img
```

Save and exit.

## Enabling NetworkManager

Now enable NetworkManager so that networking starts automatically when you boot into your system.

bash

```bash
systemctl enable NetworkManager
```

## Finishing the installation

Everything should now be configured.

Exit the chroot environment.

bash

```bash
exit
```

Unmount all mounted partitions.

bash

```bash
umount -R /mnt
```

Now reboot.

bash

```bash
reboot
```

When your computer restarts, remove your installation USB and boot into your newly installed Arch Linux system.

Log in with the user account you created and update your system by running.

bash

```bash
sudo pacman -Syu
```

For any issues in this guide, make an issue on GitHub.