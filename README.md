# pracMonFeather
MIDI Practice Monitor for a Feather Microcontroller

&copy;2024 Rob Cranfill

# Purpose
Elevator Pitch: A FitBit for MIDI keyboards! Tells you how much you have practiced via various metrics.

# Design Goals
Something that plugs into the USB port of a MIDI keyboard; no external power requirement would be nice.

# Hardware Requirements for this project
* Adafruit "RP2040 with USB A Host" (Adafruit part number xxxx)
* Adafruit 0.91" OLED Display (P/N 4440)
* Power supply - wall wart or lithium battery?

# Software Requirements
(See requirements.txt for latest)
* CicruitPython
* Adafruit support libraries

# Open Issues
* How to preserve data across restarts?
  * Write to a file, I assume. When? How often?

  
