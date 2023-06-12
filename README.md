# cr-10S-marlin
custom marlin configuration for the Creality CR-10S for the 4.2.7 board with TMC 2225 stepper drivers (in Marlin settings it's TMC2208).

The Z Axis had to be inverted for me, probably because of the dual Z axis adapter i used.

No bl-touch in this one. If you want to use that for bed leveling, you have to compile the firmware yourself. Use the ender 3 or cr-10 example config on the official marlin github for reference.
My config is in the config_files directory


the firmware version is marlin 2.0.9.6.
To install, put the firmware-20230527-185402.bin on your sd card with nothing else on it, put the card into your turned off printer, turn it on and wait a few seconds for it to boot into marlin. 
That's it, dont forget to remove the file from the sd card when you're done, unless you want to flash it again.
