# Hookup Guide

Looking to program your AVR-based boards without the mess of wires and a breadboard?  In this guide we'll introduct you to the important aspects of the ICSP and how to program different types of boards with it.

- [Board Overview](/Board-Overview.md) - A look at the hardware components that make up the ICSP programmer
- [Programming an Arduino UNO](/Programming-an-Arduino-Uno.md) - A simple example of reloading a bootloader onto an Arduino UNO.
- [Programming a Custom ATMega328P using Tag-Connect](/Programming-a-Custom-ATMega328P.md) - A more interesting example of how to load a bootloader onto a custom ATMega328P based board.  In this example we'll "program the programmer"
- [Programming an ATTiny88-based Custom Board using Tag-Connect](/Programming-a-Custom-ATMega328P.md) - An even more interesting example of programming something other than an Arduino Uno clone - in this case a custom board based on an Atmega ATTiny88.


## Required Materials

To follow along with this tutorial, you will need an ICSP programmer and a target board to program.  Our tutorials include programming different types of board but we suggest starting with a standard Arduino Uno.  Additionally, you'll need a USB-C cable to plug into your computer and the Arduino IDE installed.

## Optional Accessories (not included)

While the programmer comes with a standard double-female ICSP cable, enabling it to program a board such as an Arduino Uno out of the box, that's just not something that's done very often.  The real power of this programmer is it's compatibility with Tag-Connect cables, enabling you design and program custom boards that have an ICSP interface with a much smaller footprint.  We recommend using either the Tag-Connect TC2030 Legged or, preferably, the smaller TC2030 no-leg version if space is at a premium on your custom board.  See links below for recommended cables:

- [Tag-Connect EC06-Idc 6-pin Castellated Board-Edge Connector](https://www.tag-connect.com/product/ec-06-pcb-edge-connector)
- [Tag-Connect TC2030-ICESPI Legged Cable](https://www.tag-connect.com/product/tc2030-icespi-legged-cable-for-use-with-atmel-ice?attribute_orientation=LEMTA+-+Ribbon+Connector+reversed+for+Atmel-ICE)
- [Tag-Connect TC2030-IDC-NL (No-Leg version)](https://www.tag-connect.com/product/tc2030-idc-nl)
- [Tag-Connect TC2030-CLIP-3PACK](https://www.tag-connect.com/product/tc2030-retaining-clip-board-3-pack)


