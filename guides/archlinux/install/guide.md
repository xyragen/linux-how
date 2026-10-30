# Installing Archlinux manually

Flashing Archlinux ISO, the first thing you want to do is install the ISO from
'https://fastly.mirror.pkgbuild.com/iso/2026.10.01/'.
Install the one that says .iso located at the top and sha256sums.txt located at the bottom.

Then make sure the sums are correct, if they arent reinstall it but if it is then you can start flashing it by plugging in your USB into the USB port of your PC.

 If your PC uses Windows, start by going to your downloads if your not already there, then hold the ISO file with your mouse by clicking then dragging. Drag it into the device on the side that says the name of your USB, thats where you drop it. unplug your USB

 If your PC uses Linux start by opening a terminal like a tty console by holding ctrl+alt+f4 or any unoccupied tty console. Once you have logged into your account run 'ls' then use 'cd /path/to/archiso' (replace path/to/archiso with the actual place where the ISO got installed to) then use 'mv /path/to/archiso /dev/sda/sda2' (replace /dev/sda/sda2 to the actual USB drive you have plugged into your PC)

 Once you have finished those steps, boot into your firmware interface by repetitively pressing f12 right after rebooting. Then once you are in the firmware interface disable Secure Boot because first of all its shitty and second you wont be able to boot into the archiso without a key, then you find your USB device with the archiso on it then click it. You will be in archiso, run 'sgdisk --zap-all /dev/nvme0n1' which will wipe everything off then run 'reboot' and repetively press f12 to get into the firmware interface once again. Then click your USB again then you will be inside the archiso

 Once you are in run 'ping -c 4 1.1.1.1' if it doesnt return any packets that means you arent using ethernet so get an ethernet cable, plug it into the router then to your pc. If you do not have one run 'iwctl', 'device list', 'station wlan0 scan'

