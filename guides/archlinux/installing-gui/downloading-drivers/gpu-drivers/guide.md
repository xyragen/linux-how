Installing Graphics Drivers for Arch Linux

One thing before you continue: do not paste the single quotation marks, as they only exist to separate the commands from the text. Double quotation marks indicate text meant to be pasted into whatever you are doing in the guide.

First, identify your graphics hardware by running 'lspci -k | grep -A 3 -E '(VGA|3D|Display)' '.

If you have a modern AMD GPU, run 'sudo pacman -S mesa vulkan-radeon lib32-mesa lib32-vulkan-radeon'.

If you have a modern Intel GPU, run 'sudo pacman -S mesa vulkan-intel lib32-mesa lib32-vulkan-intel intel-media-driver'.

If you are running Arch Linux inside VirtualBox, install the guest utilities by running 'sudo pacman -S virtualbox-guest-utils', then enable the VirtualBox guest service by running 'sudo systemctl enable --now vboxservice'.

For supported Turing-generation and newer NVIDIA graphics cards, you can install the open NVIDIA kernel modules by running 'sudo pacman -S nvidia-open nvidia-utils lib32-nvidia-utils'.

The nvidia-open package is intended for supported NVIDIA GPUs. Older NVIDIA graphics cards may require a different driver package. Also, if you are using a custom kernel, you may need the corresponding DKMS driver package instead.

After installing your graphics drivers, reboot your system by running 'sudo reboot'.

VirtualBox users: If you intend to use VirtualBox to run virtual machines, install the VirtualBox host packages separately. For the standard Arch Linux kernel, run sudo pacman -S virtualbox virtualbox-host-modules-arch. Then load the kernel module by running 'sudo modprobe vboxdrv'.

For USB passthrough, add your user to the vboxusers group by running 'sudo usermod -aG vboxusers $USER'. Log out and back in for the group change to take effect.