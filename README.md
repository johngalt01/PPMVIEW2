9/13/2025

PPMVIEW2.COM newest update adds bug fixes and new features. Adds Grey scale display conversion.

PPMDC.COM is a utility that just processes PPM files and adds Dithering to match the FABGL ANSI Terminal saves the output to a new image PPM file. this saves some time if you want to use ppmview2 since you can disable dithering as it has already been done.

PPMAC.COM is a utility that turns a PPM image file into RAW asci Terminal escape codes you can also alter the image offset X,Y. allows you to TYPE the VT file to the terminal for a quicker output to the display. Be aware this will make the new VT file size huge
because of the escape codes, you can easily have a file over 5mbs in size for small image. it will also take a long time to transfer these escape codes to the terminal when running at 9600baud for older machines. a black and white image can display very fast with this method then you use the transperancy option in the conversion. it was designed as a fast way to send 1-bit images like electronics schematics to the terminal.

PPMLST.COM is a utility that just prints a PPM file to your choice of Supported OKIDATA printers. its a faster 1-bit conversion and output when you just want to print an image as fast as possible. It can take hours to output a 512X384 Resolution image file.
Max res supported is 512X384 to match the FABGL Display terminal. a 512x384 image could take over 12 hours to complete to the terminal with dithering conversion. this will output to the printer in just 2-3 hours by comparision.


the GEOFF version of PPMVIEW2 has not been updated yet, there is a bug with the IBM compatable and 320 printer family where an image over 255 in width will crash the program, i have to get the newer version posted.

Updated 4/22/2025

SUPPORTED PRINTERS - OKIDATA(EPSON MODE) 320/321/320T/321T/390T/391T/520/521/590/591/192ML/192IBM
* some bug fixes
* added Okidata 192 ML printer support.
* added Okidata 192 'IBM Compatable' printer support

Added some additional test images to play with

This is my own version of the original PPMVIEW program by eightbitswide
https://github.com/eightbitswide/ppmview

Requires FABGL VGA32 ANSI Terminal or GEOFF Terminal version now available.

I rewrote and extended the functionality of the original PPM viewer.
you can choose to turn dithering on or off to speed up the display a little.
choose to print the display to a okidata printer on the LST: port.
even some brightness adjustment.
Inverting the image output.

Dithering is tied to the 4 levels of color the ANSI Terminal allows for a total of 64 colors.
printing is 1-bit dither, all based on Floyd–Steinberg.

Geoff Terminal is 1-bit dither or 1-bit raw output.

![DSCN5645](https://github.com/user-attachments/assets/3efd3905-7d73-4c88-ac2e-c07a97e4275d)
![DSCN5647](https://github.com/user-attachments/assets/b0804be3-4dbc-401f-a78e-c09deb285ee4)
![DSCN6346](https://github.com/user-attachments/assets/f4efdf59-a600-4785-a676-6925dbd51c5e)
