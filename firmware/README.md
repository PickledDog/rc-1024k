# Firmware
This directory contains firmware source and binaries for the board. As of now, it only contains changes to RomWBW.

## RomWBW changes
These changes apply to RomWBW 3.1.1 (the current `dev` branch at time of writing). They were applied to RomWBW 3.1.1-pre.71 on 2021/04/19. The config **.asm** should be placed in `Source/HBIOS/Config`. A prebuilt ROM image is provided. To build this image under Windows, run `BuildShared`, then `BuildROM RCZ80 pd1024` (both from `Source`).
