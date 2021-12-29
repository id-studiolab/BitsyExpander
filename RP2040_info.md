# BitsyExpander RP2040
Grove Breakout and WiFi board for Adafruit's [ItsyBitsy RP2040](https://www.adafruit.com/product/4888).

This page refers to an adaptation of the original BitsyExpander for ItsyBitsy M4, intended for the lower cost ItsyBitsy RP2040.
Both are electrically identical, the version described here features an amended silkscreen targeting the RP2040.

## Pin information
Contrary to the ItsyBitsy M4, it has less analog input and no true analog output pins. While RP2040 has more limited analog capabilities, it allows for flexible configuration and use of its GPIO pins. This can be advantageous, but may require more careful planning and research.

**For detailed information on the ItsyBitsy RP2040's pinout, see Adafruit's documentation:**  

[Adafruit ItsyBitsy RP2040](https://learn.adafruit.com/adafruit-itsybitsy-rp2040)


## Arduino support
[CircuitPython](https://circuitpython.org/board/adafruit_itsybitsy_rp2040/) is recommended for the ItsyBitsy RP2040. 
However, there is community support for using it with Arduino.

**Relevant links:**  

[Earlephilhower's Arduino Pico Core](https://github.com/earlephilhower/arduino-pico/#arduino-pico)  
[Program RP2040 in Arduino (Adafruit)](https://learn.adafruit.com/rp2040-arduino-with-the-earlephilhower-core)


This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
