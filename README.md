# Ender-3 Pro Marlin 1.1.9.1 Config
This config for Marlin 1.1.9.1 Firmware for Ender-3 Pro (Mainboard Version 1.3.1) incl. BLTouch settings and M600 enabled (for Filament Change and Runout Sensor via OctoPrint).

The settings for BLTouch were taken from Daniel Brooke Peig (https://www.danbp.org/p/en/node/136?page=0). Other changes to the Marlin Config were taken from the original Ender-3 Pro firmware (speed, babystepping etc.). 

I use the original BLTouch mount that came with the kit, so the settings for X and Y offset are set to -44 and -5. If you are using a different mount for BLTouch, you probably have to change the offset values in lines 787 and 788 in the file Configuration.h. All the changes I made to the config are marked with // custom setup BP.

Since the original Ender-3 Pro mainboard has limited memory, I had to **disable the SD Card support** to get the features activated that are necessary for BLTouch and the M600 GCode command (needed for the Filament Runout Sensor and Filament Change/Nozzle Parking features).

**I am not responsible for any damage that happens to your printer when using my configuration file(s)!**

## FAQ:
**Q:**
How do I compile the Marlin 1.1.9.1 firmware?
**A:**
Daniel Brooke Peig made a tutorial. Check out his Wiki page: https://www.danbp.org/p/en/node/136?page=0

**Q:**
How do I flash the firmware to the printer?
**A:**
Please see the tutorial at this page: https://medium.com/@jethro_20307/creality-ender-3-pro-bltouch-v3-1-marlin-1-1-9-1-e3512ed9c81a

