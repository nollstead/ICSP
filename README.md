# 3.3v/5v In-Circuit Serial Programmer

## Product Overview

Looking to easily either load a bootloader or directly program an Arduino Uno but don't like messing with wires?  How about other AVR products such as an ATTiny45 or ATTiny88 that use 3.3v logic?  This handly ICSP programmer allow you to easily program either commercial or custom AVR-based board with ease.  It comes preloaded with the ArduinoISP sketch so it works within the Arduino IDE environment (no complex AVRDude command-line strings needed).  The onboard CH340C automatically converts USB signals to serial and is recognized by Windows, so no drivers or separate FTDI board required.  Check out our [Hookup Guide](/Hookup-Guide.md) to see how easy it is to program your 5v or 3.3v targets.

## Features & Specs

- Standard ICSP programmer for AVR-based boards
- USB-C connector
- Preloaded with ArduinoISP sketch
- Transmit (Tx) and Receive (Rx) LEDs
- Adjustable output voltage of 5.5v or 3.3v via jumper.  Automatically level shifts data pins based on selected target voltage
- Arduino-IDE compatible.  No need for complex AVRDude commands
- Keyed ICSP connector eliminate accidental mis-wiring
- Includes 6-pin double female cable for connecting to standard Arduino ICSP header.  Compatible with Tag-Connect cables for lower profile custom boards (See Accessories)

## Documentation

- [Schematic](/schematic.pdf)
- [Hookup Guide](/Hookup-Guide.md) - Basic hoookup guide for the ICSP

## Optional Accessories (not included)

- [Tag-Connect EC06-Idc 6-pin Castellated Board-Edge Connector](https://www.tag-connect.com/product/ec-06-pcb-edge-connector)
- [Tag-Connect TC2030-ICESPI Legged Cable](https://www.tag-connect.com/product/tc2030-icespi-legged-cable-for-use-with-atmel-ice?attribute_orientation=LEMTA+-+Ribbon+Connector+reversed+for+Atmel-ICE)
- [Tag-Connect TC2030-IDC-NL (No-Leg version)](https://www.tag-connect.com/product/tc2030-idc-nl)
- [Tag-Connect TC2030-CLIP-3PACK](https://www.tag-connect.com/product/tc2030-retaining-clip-board-3-pack)



## License Information

This hardware is released under [Creative Commons Share-alike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

