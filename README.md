# Ender-3 Pro Marlin_1.1.9.1 Config
This config for Marlin 1.1.9.1 Firmware for Ender-3 Pro (Mainboard Version 1.3.1) incl. BLTouch settings and M600 enabled (for Filament Change and Runout Sensor via OctoPrint).

The settings for BLTouch were taken from Danial Brooke Peig (https://www.danbp.org/p/en/node/136?page=0). Other changes to the Marlin Config were taken from the original Ender-3 Pro firmware (speed, babystepping etc.). 

I use the original BLTouch mount that came with the kit, so the settings for X and Y offset are set to -44 and -5. If you are using a different mount for BLTouch, you probably have to change the offset values in lines 787 and 788 in the file Configuration.h. All the changes I made to the config are marked with // custom setup BP.


