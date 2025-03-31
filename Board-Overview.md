# Board Overview

- USB connector
- Power Switch
- CH230C
- ATMega328P
- Texas Instruments TXU0304 Level Shifter
- Tag-Connect TC2030-IDC-NL programming interface -- This header is used to program the onboard ATMega328P with a bootloader.  The board comes with a bootloader and the ArduinoISP sketch pre-loaded so it's unlikely you'll use this but it's available if you ever want to install a new bootloader.  
- 16MHz Crystal Oscillator
- 3.3v LDO Voltage Regulator
- Voltage Jumper
- ISP Interface (output) - This is the SPI interface used to program your target device.  The pinout matches the standard ICSP header format on the Arduino Uno

   ![ICSP Header](/images/ICSPHeader.jpg)