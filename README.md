![20230601_163252](https://github.com/DariuszJJ/Ortur-Obsidian-Klipper/assets/45244319/81b7110f-b02f-465d-90a4-df3e9be34c00)



# Ortur-Obsidian-Klipper
Ortur Obsidian Klipper printer.conf for original Mainboard.In my case using a Klipper significantly improved the quality and speed-up printouts. 
The original software lacked PID BED and input shaper. Setup requires basic Klipper knowledge
https://www.youtube.com/shorts/8Og5eOHv3mc
- original display does not work ( preferred android tablet)

- PSU control does not work

##Use the file and configuration at your own risk!

This file contains common pin mappings for the ORTUR OBSIDIAN
To use this config, the firmware should be compiled for the
STM32F103 with a "64KiB bootloader" and communication interface (Serial (on USART1 PA10/PA9)).

The "make flash" command does not work on the ORTUR OBSIDIAN. Instead,
after running "make", copy the generated "out/klipper.bin" file to a
file named "OPF_OBS_V62_MARLIN_20230325.bin" put on an SD in ~/system/ card and then restart the ORTUR OBSIDIAN
If there is a problem with communication, I recommend using the UART output on the motherboard and a USB adapter.
![20230611_080942](https://github.com/DariuszJJ/Ortur-Obsidian-Klipper/assets/45244319/20a3ae5f-f4ba-4a1a-82c2-9bbae99f9a03)

