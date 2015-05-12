# bdfparse
I use this program to produce fonts for bitmap-dot displays like Nokia 5150 display device. It converts symbols from the standard UNIX bdf font files to raw bitmap for the device (well, bdf files also contain bitmap, but this program perform the transposition of the bitmap and some padding if necessary).

This program takes BDF file and symbol code as input and produces a string of bytes that should be send to device to produce corresponding symbol. You can specify multiple symbol codes, separated by comma. 

Newer Linux systems has bitmap fonts distributed in PCF format. BDF files can be obtained from the pcf file using pcf2bdf utility.
