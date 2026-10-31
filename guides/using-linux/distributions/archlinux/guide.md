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
ping -c 3 1.1.1.1
---------------------

if you are connected automatically you are probably means you are using ethernet, but if it doesnt return any packets then connect to your internet by running

------
nmtui
------

then set your system clock by running

---
timedatectl set-ntp true
---

-----------------
sgdisk --zap-all /dev/nvme0n1 # wipes everything off of your drive
-----------------

and repartition your disks by running 

---------------------------------------------------------
cfdisk /dev/nvme0n1 # assuming your drive name is nvme0n1
---------------------------------------------------------

set the drive label to GPT then make a new label by selecting new and then entering 1G and make the type EFI System and new another new label which you will leave for cfdisk to set everything by default then select write to write the new partition changes to your drive and enter yes not y or anything else and quit.

You will return to the archiso which you will need to partition your drives (this one shows how to partition your drive in btrfs and ext4 after) by running 

### Formatting using BTRFS
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
ping -c 3 1.1.1.1
---------------------

if you are connected automatically you are probably means you are using ethernet, but if it doesnt return any packets then connect to your internet by running

------
nmtui
------

then set your system clock by running

---
timedatectl set-ntp true
---

-----------------
sgdisk --zap-all /dev/nvme0n1 # wipes everything off of your drive
-----------------

and repartition your disks by running 

---------------------------------------------------------
cfdisk /dev/nvme0n1 # assuming your drive name is nvme0n1
---------------------------------------------------------

set the drive label to GPT then make a new label by selecting new and then entering 1G and make the type EFI System and new another new label which you will leave for cfdisk to set everything by default then select write to write the new partition changes to your drive and enter yes not y or anything else and quit.

You will return to the archiso which you will need to partition your drives (this one shows how to partition your drive in btrfs and ext4 after) by running 

### Formatting using BTRFS
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

create the necessary directories 

---------------------------------------------------------
mkdir -p /mnt/{boot,home,.snapshots}
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

### Formatting using EXT4
first run the command below to format your boot partition if you havent already
---------------------------------------------------------
mkfs.fat -F32 /dev/nvme0n1p1
---------------------------------------------------------

then format the root partition by running

---
mkfs.ext4 /dev/nvme0n1p2
---

and mount the root partition by running

---
mount /dev/nvme0n1p2 /mnt
---

and create the boot directory by running 

---
mkdir -p /mnt/boot
---

and mount the efi partition by running

---
mount /dev/nvme0n1p1 /mnt/boot
---

Once you have finished mounting and that system commands bullshit, install the base system for btrfs by running 

---------------------------------------------------------
pacstrap -K /mnt base linux linux-firmware btrfs-progs networkmanager sudo nano grub efibootmgr
---------------------------------------------------------

but for ext4 use this command instead (excludes btrfs-progs)

---------------------------------------------------------
pacstrap -K /mnt base linux linux-firmware networkmanager sudo nano grub efibootmgr
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

-----------------------------------------------
create the necessary directories 

---------------------------------------------------------
mkdir -p /mnt/{boot,home,.snapshots}
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

### Formatting using EXT4
first run the command below to format your boot partition if you havent already
---------------------------------------------------------
mkfs.fat -F32 /dev/nvme0n1p1
---------------------------------------------------------

then format the root partition by running

---
mkfs.ext4 /dev/nvme0n1p2
---

and mount the root partition by running

---
mount /dev/nvme0n1p2 /mnt
---

and create the boot directory by running 

---
mkdir -p /mnt/boot
---

and mount the efi partition by running

---
mount /dev/nvme0n1p1 /mnt/boot
---

Once you have finished mounting and that system commands bullshit, install the base system for btrfs by running 

---------------------------------------------------------
pacstrap -K /mnt base linux linux-firmware btrfs-progs networkmanager sudo nano grub efibootmgr
---------------------------------------------------------

but for ext4 use this command instead (excludes btrfs-progs)

---------------------------------------------------------
pacstrap -K /mnt base linux linux-firmware networkmanager sudo nano grub efibootmgr
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
%wheel ALL=(ALL:ALL) all
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

and make sure that it shows that it added entries for something like vmlinuz-linux because that means grub found your OS

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