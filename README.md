# threadprofile
Companion to Mark Ganson's Thread Profile in FreeCAD

This script is meant to be a companion to Mark Ganson's Thread Profile workbench for FreeCad

NOTE: this script requires the bc calculator program, which is most likely in the repositories
for your distribution, but may not be installed.

If you are using a debian type distribution:

$ sudo apt install bc

This script is meant to provide the necessary input to the VThreadProfile to do US Acme threads 
(also known as painters poles in the US), with the Thread Profile

usage: threadprofile 5/8 8     <-- meaning 5/8 inch by 8 threads per inch

To input a value greater than 1 inch, like the 1-1/8 inch thread size, simply do this:

$ threadprofile 1+1/8 5

This has been tested using a 5/8-8 rod, and there is just enough clearance to fit snugly.

You MUST calibrate your 3D Printer for your part to fit real world objects, or this will not work.
It is suggested you print a 20mm cube, and make sure to adjust your printer and/or gcode to make as
good a fit as possible.

Other common sizes for Acme threads are 3/4-6, 7/8-5, 1-5.

