# Installing Graphics Drivers for Archlinux
One thing before you continue, do not paste the single quotations as it only exists to seperate the commands from the text and the double quotes are for text meant to be pasted into whatever you are doing in the guide.

First, identify your hardware by running 'lspci -k | grep -A 3 -E '(VGA|3D|DISPLAY)' '.

If you have a modern AMD GPU then run 'sudo pacman -S mesa vulkan-radeon lib32-mesa lib32-vulkan-radeon'.

If you have a modern Intel GPU then run 'sudo pacman -S mesa vulkan-intel lib32-mesa lib32-vulkan-intel intel-media-driver'.

If you are on VirtualBox run 'sudo pacman -S virtualbox-guest-utils' then get guest additions run 'sudo pacman -S virtualbox-guest-utils' and then run 'sudo systemctl enable vboxservice'.

For supported turing generation and newer generation nvidia graphics cards run 'sudo pacman -S nvidia-open nvidia-utils lib32-nvidia-utils'

Then reboot by running 'sudo reboot' then run 'sudo modprobe vboxdrv' to load the kernel module and for the USB passthrough add your user to the vboxuser group by running 'sudo usermod -aG vboxusers $USER'