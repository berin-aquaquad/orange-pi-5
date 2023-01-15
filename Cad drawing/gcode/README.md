![heatsink block milling path](https://user-images.githubusercontent.com/15570512/212489789-81d853e7-2bee-4334-8f82-cfd8878887ea.png)


The TAP file is a GCODE file for running a cnc machine. I have posted a file for both the heatsink block and mount brackets. If anyone has a cnc machine that can mill aluminum. This file expects a 1/8th milling bit, it expects a block of aluminum 12mm or .5" thick. The top of the tooling material is prob to zero. The tool path will mill below the thickness/depth of the stock during the two hole milling cycles and the final cut out. Account for those actions, the feed rate is 20mm/min. With out a clearing system like forced air and or flood coolent/lube, the deep cuts may need to be manually cleared. If the aluminum chips are not cleared then the the milling job may risk aluminum chip welding. That never ends well.

The .E10 file is an ESTLcam file. I love ESTLcam, everything about it is easy. There are a few areas I'm not a fan of but that could have been designed different but I can work with it.
It does have some small issues and there is a bug in the coding that has to do with standard/metric units option-settings. I've asked the creater manytimes only to be brushed off. As long as the software options settings are correct on the UI everything is accurate. The problem is a "rounding" issue to the .xxx point rounding up. so... .005 would be rounded upto .01. You can see the issue with gcode output in regards to a tooling path and bit size.

![steel bracket cnc cut out](https://user-images.githubusercontent.com/15570512/212523265-c49f42c0-9e1f-4290-9cee-474ecd449edc.jpg)
