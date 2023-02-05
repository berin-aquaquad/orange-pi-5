![heatsink block milling path](https://user-images.githubusercontent.com/15570512/212489789-81d853e7-2bee-4334-8f82-cfd8878887ea.png)


The TAP file is a GCODE file for running a cnc machine. I have posted a file for both the heatsink block and mount brackets. If anyone has a cnc machine that can mill aluminum. This file expects a 1/8th milling bit, it expects a block of aluminum 12mm or .5" thick. The top of the tooling material is prob to zero. The tool path will mill below the thickness/depth of the stock during the two hole milling cycles and the final cut out. Account for those actions, the feed rate is 20mm/min. With out a clearing system like forced air and or flood coolent/lube, the deep cuts may need to be manually cleared. If the aluminum chips are not cleared then the the milling job may risk aluminum chip welding. That never ends well.

The .E10 file is an ESTLcam file. I love ESTLcam, everything about it is easy. There are a few areas I'm not a fan of but that could have been designed different but I can work with it.
It does have some small issues and there is a bug in the coding that has to do with standard/metric units option-settings. I've asked the creater manytimes only to be brushed off. As long as the software options settings are correct on the UI everything is accurate. The problem is a "rounding" issue to the .xxx point rounding up. so... .005 would be rounded upto .01. You can see the issue with gcode output in regards to a tooling path and bit size.

![steel bracket cnc cut out](https://user-images.githubusercontent.com/15570512/212523265-c49f42c0-9e1f-4290-9cee-474ecd449edc.jpg)

Micro desktop sides cut finally. I have modified the DXF files only so far. The main .RSDOC file I'll update when I get around to it, but I changed the dimentions of the 45 degree vents and spacing. I also added straight lines in the vents that needed them. That allows anyone who plans to mill the deesign. To preform an engrave or straight cut rather then milling the "pocket" or hole function. I may post the GCODE files if I get any requests, if interested its setup for a 1/8th or 3.125mm two flute upcut bit running 15k rpm or greater. With a feed rate of 50mm/min two passes, then a finishing cleanup pass full depth at 150mm/min. Its true I could mill it faster BUT I mounted it with dbl sided foam tape. Not worth the risk of deflection warping the cut.

![20230204_213044](https://user-images.githubusercontent.com/15570512/216799617-0b144c5e-db34-4da9-807d-260743f343f1.jpg)
