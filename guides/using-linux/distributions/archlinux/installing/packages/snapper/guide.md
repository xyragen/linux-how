# Installing Snapper

run

---
sudo pacman -S snapper
---

to set it up run

--- 
sudo umount /.snapshots
---

then

---
sudo rmdir /.snapshots
---

then create the snapper root filesystem by running

---
sudo mkdir /.snapshots
---

and remount the subvolume by running 

---
sudo mount -a
---

and set its permissions by running

---
sudo chmod 750 /.snapshots
---

## Optional

### Configure Automatic Snapshots

run

---
sudo nano /etc/snapper/configs/root
---

then find and config the settings to match this:

TIMELINE_CREATE="yes"
TIMELINE_CLEANUP="yes"

NUMBER_CLEANUP="yes"
NUMBER_LIMIT="10"
NUMBER_LIMIT_IMPORTANT="5"

TIMELINE_LIMIT_HOURLY="5"
TIMELINE_LIMIT_DAILY="7"
TIMELINE_LIMIT_WEEKLY="4"
TIMELINE_LIMIT_MONTHLY="0"
TIMELINE_LIMIT_YEARLY="0"

### Enable Snapper timers

run

---
sudo systemctl enable --now snapper-timeline.timer
---

and also run

---
sudo systemctl enable --now snapper-cleanup.timer
---

then do a check to see if they are running by running this command

---
systemctl list-timers | grep snapper
---

## Basic commands to learn

---
sudo snapper -c root create --description "First Snapshot"
---

the command above makes a snapshot with the description of "First Snapshot"

breakdown: 'root create' creates a snapshot for the root partition and the --description flag allows you to add a description for the snapshot