# Board Overview

- USB connector - This is the data and power input to the programmer. 
- Voltage Jumper - Use this to power your target at either 5v or 3.3v.  
- Texas Instruments TXU0304 Level Shifter - Provides 3.3/5v level shifting for MISO, MOSI, nRESET and SCK signals based on selected voltage (from voltage jumper)
- CH230C - Converts USB signals to serial as required for for target board.  
- ATMega328P - This is the main processor for the ICSP board.  Since this board uses an ATMega328P it can be thought of and treated like an Arduino Uno, making it easier to use.  
- Tag-Connect TC2030-IDC-NL programming interface -- This header is used to program the onboard ATMega328P with a bootloader.  The board comes with a bootloader and the ArduinoISP sketch pre-loaded so it's unlikely you'll use this but it's available if you ever want to install a new bootloader.  
- 16MHz Crystal Oscillator
- 3.3v LDO Voltage Regulator - Used to convert the 5v USB power to 3.3v when the 3.3v jumper option is used.
- ISP Interface (output) - This is the SPI interface used to program your target device.  The pinout matches the standard ICSP header format on the Arduino Uno

   ![ICSP Header](/images/ICSPHeader.jpg)