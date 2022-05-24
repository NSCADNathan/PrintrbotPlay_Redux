Klipper Documentation: https://www.klipper3d.org/Overview.html

Step by Step Guide starting from a fresh install of octoprint.

cd klipper
git pull
sudo service klipper stop

ls /dev/serial/by-id/*
Copy the output and paste it to the end of this command

make flash FLASH_DEVICE=

So that it looks similar to this:
make flash FLASH_DEVICE=/dev/serial/by-id/usb-Synthetos_TinyG_v2_021303215d0403-if00

sudo service klipper start

After flashing completes and you have started klipper, power cycle the simple pro by turning it off for 10 seconds and back on.

