# SE-SE30-Compact-Card
SE &amp; SE30 Compact Card

Released under CC4.0 BY-NC-ND

This item uses the RGBtoHDMI created by IanSB using the public release:

https://github.com/IanSB/RGBtoHDMI?tab=readme-ov-file

You will need to provide a SD card and install the RGBtoHDMI software.
Configer the card as RGB and set your profile to SE30 in the menu.

You can order the boards from JCL and have them assemble most of the items
on the underside for you by uploading the BOM and PNP files. The only item 
you will need to add to the bottom will be the ATTINY85 after you program
it with the hex code provided.

The top board items you will need to purchase. A file is provided called
ExtraItems.xlsx. I buy these from mouser. You can use other source as you wish.

All the 2 pin header locations that provide 5v, 12v, Power LED etc can be
populated with normal header or I use JST sockets and make my own wires as
needed. J7 & J10 are the LEDs for the RGBtoHDMI with J3 being the single button
mode option for the RGBtoHDMI but needs to be inabled in the .TXT file to work.

J13 is for the power on where a switch can be connected to turn the system on/off
or leave the jumper on it to turn on once the power is connected to the Pico.

The fan needs to be a 12V fan similar to this one:

https://www.amzn.com/B0CWXKGSD3

There is a pot on the board by the ATTINY85 so you can adjust the temp
sensativity as to how soon the fan will start spinning.

THe PicoATX we have used is:

https://www.amzn.com/B0D2W3Z4VV
