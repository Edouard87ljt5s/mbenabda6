This is a STM32F030F4 VGA library + project for HaD 2016 Contest Entry.

Project webpage: 
https://hw-by-design.blogspot.com/2018/07/low-cost-vga-terminal-module-project.html

The individual license(s) are in each directories.

Directories:
------------------------------------------------------------------------------
font conv/ 
- source code + Windows console executable for a font conversion program.
It imports GLCD font Creator file and converter it to a C font table
of the comverted scan line bitmaps that is to be used with the VGA library.

- The converter is compiled using Pelles C
http://www.pellesc.de/index.php?page=start&lang=en

- "GLCD Font Creator" MikroElektronika
http://www.mikroe.com/glcd-font-creator/

- Project webpage:
https://hw-by-design.blogspot.com/2018/07/low-cost-vga-terminal-module-project.html

Code in this directory is licensed under "Simplified BSD License"

-------------------------------------------------------------------------------
STM32F030F4/Hardware/LT Spice Simulation
files in this directory is licensed under "Simplified BSD License"

-------------------------------------------------------------------------------
STM32F030F4/Hardware/Sketchup 3D Model
Creative Commons 4.0 Attribution-NonCommercial-NoDerivs International
http://creativecommons.org/licenses/by-nc-nd/4.0/

This is to prevent someone photoshopping this as their own project for crowd-funding 
scams. You are free to generate your own model using Eagleup from your new layout.

-------------------------------------------------------------------------------
STM32F030F4/Hardware/
Schematic/Layout is distributed with Creative Commons 4.0 Attribution-NonCommercial
http://creativecommons.org/licenses/by-nc/4.0/

If you want to sell this and want a different licensing term, please contact me.

-------------------------------------------------------------------------------
STM32F030F4/Firmware/

Source code distributed under GPLV3.

--------------------------------------------------------------------------------
Update:
Madis Kaal wrote 10/24/2017 at 23:22
I've branched the code and added VT100 emulation,
see https://github.com/mastmees/STM32F030F4-VGA
