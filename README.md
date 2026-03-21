# Creality-Ender-5-firmware-update fix for non chinese.
Newest update available from Creality today 3.21.2026 is Ender-5 PlusMarlin1.1.6-HW-V2.2-SW-V1.70.3BLTouchMulti for printers using v2.2 seen on the motherboard. 

updating the firmware in Ender 5 plus needs renaming 2 files before flashing. 

I needed to go into the DWIN_SET folder on the SD card and rename two .bin files which use Chinese (Hanzai) text.
13触控配置文件.bin renamed to 13_C_Touchprofiles.bin
14变量配置文件.bin renamed to 14_C_Variableconfigurationfiles.bin
