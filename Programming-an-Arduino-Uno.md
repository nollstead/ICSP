# Programming an Arduino Uno

For this example we'll start off keeping it simple, to show the simplest use case - replacing the bootloader on an Arduino Uno.  Admittedly, this isn't something that done very often but when you need it you need it - and it serves as a good starting point for working with the ICSP programmer.

## Connect the Programmer

1.  Connect the programmer to your computer using a USB-C cable and take note of the COM port assigned by Windows.  You can find that in Device Manager under Ports; look for an entry lableled USB-Serial (CH340).  In my case it's assigned to COM port 13, as shown below, though this may differ in your environment.

     ![COM Port](/images/COMPort.png)

2.  Since the Arduino UNO is a 5v device, ensure the jumper pin is in the 5v position (right two pins)

3.  Connect the 6-pin cable to the programmer and the target Uno's ICSP header.  Note that the cable and connector on the programmer are keyed to ensure correct placement, however, the Uno's ICSP header is not - so be sure to correctly line up the cable on the Uno with the Red wire on the top right, as shown below

## Configure the Arduino IDE

Configure your Arduino IDE to use the COM Port (identified above) of the programmer, the Arduino as ISP programmer and the target board.  In this example we're programming an Arduino Uno we'll use COM 13 and "Arduino as ISP" for the programmer and Arduino Uno for the target board.  

## Uploading a new Bootloader via the Arduino IDE

To upload a new bootloader, just click Tools -> Burn Booloader.  You'll see the Tx and Rx lights flash for a few seconds then a message in the IDE stating that the booloader has been uploaded successfully.  From here you can either upload a sketch as normal using the Uno's built-in USB connector or continue to the next section to upload a sketch using the programmer.

## Uploading a Sketch via the Arduino IDE

In addition to burning a bootloader, you can also use the programmer to upload a sketch to your target board.  Just load your sketch, ensure you have the same Board, Port and Programmer settings as above, and click Sketch -> Upload using Programmer.

To run your sketch, either disconnect the ICSP cable or remove the power jumper and connect your target board to it's own power.  


