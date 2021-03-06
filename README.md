

The MicroPython project
=======================


This is a fork of micropython repository which aims to port micropython
on Atmel's SAM3X (Arduino Due) microcontrollers.


## Status: 
This port is still in Beta.

## Docs
See What's supported section in ``atmel-sam3x/``


Major components in this repository:
- py/ -- the core Python implementation, including compiler, runtime, and
  core library.
- tests/ -- test framework and test scripts.
- docs/ -- user documentation in Sphinx reStructuredText format.


Additional components:
- **atmel-sam3x/ -- a port of micropython for SAM3X (Arduino Due) board.**
- bare-arm/ -- a bare minimum version of MicroPython for ARM MCUs. Used
  mostly to control code size.
- teensy/ -- a version of MicroPython that runs on the Teensy 3.1
  (preliminary but functional).
- pic16bit/ -- a version of MicroPython for 16-bit PIC microcontrollers.
- cc3200/ -- a version of MicroPython that runs on the CC3200 from TI.
- esp8266/ -- an experimental port for ESP8266 WiFi modules.
- unix/ -- a version of MicroPython that runs on Unix.
- stmhal/ -- a version of MicroPython that runs on the PyBoard and similar
  STM32 boards (using ST's Cube HAL drivers).
- minimal/ -- a minimal MicroPython port. Start with this if you want
  to port MicroPython to another microcontroller.
- tools/ -- various tools, including the pyboard.py module.
- examples/ -- a few example Python scripts.

The subdirectories above may include READMEs with additional info.


