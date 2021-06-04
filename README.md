# pi-pico

Useful utility commands for developing with the Raspberry Pi Pico on a
Raspberry Pi.

Tested on a Raspberry Pi 4 Model B running Raspberry Pi OS.

## pif - Pico Flasher

Upload an elf file to a Raspberry Pi Pico running in SWD mode.

Usage: pif FILE<br>
Eample: pif blinky.elf

## pir - Pico Reset

Reset a Raspberry Pi Pico running in SWD mode.

Usage: pir

## cmaked - CMake Debug

Generate files for a debug build.

Usage: cmaked

## oocd - Pico Open On-Chip Debugger

Start openocd for a Raspberry Pi Pico.

Usage: oocd

## gdbm - Pico Debugger

Start the GNU debugger and run the following commands:

target remote localhost:3333<br>
load<br>
monitor reset init<br>
break main<br>
continue<br>
layout src

Usage: gdbm FILE<br>
Eample: gdbm blinky.elf

