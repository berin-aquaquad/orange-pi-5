# ORANGE-PI-5 
#                                      KEEP CHECKING BACK I UPDATE THIS GIT REPO OFTEN.
#              FIRST OPI5 IN THE WORLD WITH A REAL MOUNTED ICE TOWER HEATSINK! Now that my OPI5 has a full suite of heatsinks on it. My next focus is on starting the build of the micro desktop case and OS. I believe the first part I'll build is the SBC mounting plane. That will give me something to mount to then I'll start the main body 3d print.

![20230117_181448](https://user-images.githubusercontent.com/15570512/213040467-bef33e19-85ca-407a-9efc-6b4d8a62f26c.jpg)

![opi5 micro desktop back and side view](https://user-images.githubusercontent.com/15570512/210899034-5617d4ca-1f99-4545-9630-c1aaf9792690.jpg)

![opi5 micro desktop heatsink standoff mount bracket](https://user-images.githubusercontent.com/15570512/212485847-4f845119-6474-4ce0-8fec-bec8516d64f3.jpg)

![opi5 micro desktop dimensions](https://user-images.githubusercontent.com/15570512/212555028-3c1645ce-741b-4935-843d-13c97821a9f1.jpg)
The core body is 62mm wide



OPI5 open micro desktop case design, with a split body for two options. Main feature printable on smaller cnc machines, second feature is the ablity to have custom front and back desgined panels. Some may need ports on the back of the shell. Other people may desire features like lcd(s) and headers that are on the back to be on the front. Its a more useful design.

1/22/2023 I have been endlessly overwhelmed by my employer. I was planning on starting to build parts for the case yesterday 1/21 SAT., but I was tasked with designing and 3d printing. Inclusion mold parts for a many millions of dollars luxury yacht. That being said I just got a chance to test my opi5 today sunday. And I apear to have a DOA dead unit out of the box. As of this moment this project is on hold indefinitely until I get a working OPI5. I am very angry and very pissed off. My unit will not power on period, no signs of life nothing. Its 100% dead out of the box.

1/21/2023 I will be cutting the acrylic panel(s) today starting with the SBC mount panel first. I have not cut 1/8th acrylic on my cnc before so I may run into a bit of trial and error figuring the best milling bits out feeds/speeds.

1/16/2023 Ok looking for feed back https://www.amazon.com/Duttek-Degree-Extension-Motorcycle-Dashboard/dp/B08RRYMXB6 https://www.amazon.com/Poyiccot-Extension-Female-Extender-Straight/dp/B086YBP5VW Two examples of USB-C adapter which do you guys like? also USB-c to the front or back of the micro case? 
*************** This is the spacer/stand off kit I have purchased https://www.amazon.com/dp/B08DMSNB8X This is the kit for mounting the OPI5. All spacings will be based off of these when I get them. stay tuned.

1/17/2023 BIG update I have just mounted my heatsink to the OPI5 it LOOKS AMAZING. Now that I have my heatsinks mounted My next step is moving to to software.

1/15/2023 Unbelievable, I have to order a kit of plastic stand off mounts for the OPI5 project. I have a huge kit and its just ….. ? GONE ? In any case the brackets are built sanded and “dry” fitted. Its a perfect fit but still dont have the standoffs,so I cant assemble anything. Very pissed off, I’m 99.999999 sure I tossed the sorted box last year along with a bunch of trash and excess useless empty sorting boxes of like size kind. By design the bracket I designed and built clears everything. No feature on the OPI5 SBC is blocked between connectors and buttons.

1/14/2023 tonight, I found the screws I need FUI the cooler I described uses 2.5mm screws. I have picked up some 1/16th sheet steel and will try my hand and milling the brack design with my cnc. Its not designed for steel but is ok for aluminum. I do have some 4 flute bits so we shall see. **** tonight update part two, cutting steel sheet metal on my cnc machine...??..??? and its going REALLY well. I will post photos when the milling job is done. ******** last post for the night just before midnight. The steel frame bracket has been cut and is pictured in the cad/gcode folder have a look. Its the first noncad image I've posted.

1/14/2023 small update, my aluminum block has been cnc milled (I'll post new photos soon keep checking). I need to get some longer screws that match the heatsink and some sheet metal to create a bracket to keep the heatsink in contact with the processor (gravity strain relief). I wish I had access to a fiber or co2 metal cutting laser to make a perfect bracket. The standoff heatsink is to allow the small stick-on heatsink kit that adds cooling to the other chips on the OPI5. I also added a new folder with gcode files for the heatsink spacer block.

1/11/2023 Small update, finally got a chance to start building the aluminum spacer heatsinc block, I'll post pictures when able.

(1/7/2023) New updated cad drawing. I got my RPI4 "ice tower cpu cooling fan" heatsink. I have done the CAD adjustments I need for it to be installed. I am now creating a custom SPACER aluminum block and attachment bracket so it can even work with the OPI5. 
At this point if anyone has interest in adjustments Please contact me.

This is an ongoing project and I'll be uploading updated cad draws as they are available and pictures of the latest adjustments. If anyone has a request please send me a message via twitter #Berinmoney I'll respond as time allows. I'm also on orangepi.org forum and armbian forum. When I get closer to a final version I'll add images showing dimensions.

This design was created using Designspark mechanical https://uk.rs-online.com/web/generalDisplay.html?id=designspark%2Fdesignspark-mechanical 
I have not built the design yet as of the current date whatever today is. I will post about the start of the build when I start. I'm adding locations for all of the missing I/O to the shell as I find good parts to do so with, or learn of features. I just finished building the cad model 12/31/2022. I have currently left it as an open canvas design. The shell itself can be modified if so desired to be a mono body. Currently it's designed as a split body to be able to be printed on smaller 3d printers. The outside covers left and right are acrylic. The Mount that the OPI5 mounts to is acrylic as well. This design expects the two side panels and the sbc mount panel to be 3d printed or cnc cut or laser cut. The rest of the shell is to be 3D printed. Enjoy and please tag me as the original designer. 
FYI I'm looking for details on the OPI5. The OPI5 has an onboard RTC real time clock. and there are two test pads next to it one "grd1" the other "RTC1". That MUST be for a battery backup. I can find no details on what kind of a battery setup is needed. According to the schematic "RTC1" will be HOT with 5v DC when the SBC is running. What battery setup may be used on this? Any help would be wonderful.

Planned design additions for consideration: I need feedback on the listed or suggestions if not listed. I can create it in cad but I need dimentions to items of consideration.

* Headphone jack front or back, maybe a custom PCB to breakout audio/mic and split to a backside of the desktop header.
* USB on front.
* All other headers LCD 1 2, CAM 1 2 3, UART.
* Stats LCD on front.
* 3D printed power button to press power button on OPI5 motherboard.
* GPIO header for external access, "custom design or standard?? I need a web link example".
* RTC battery holder to make use of the onboard RTC.
* RGB Micro Desktop case LIGHTING options?
* Lithium battery backup power pack

Manuals https://drive.google.com/drive/folders/1Bre2q0bGgXQuQlYaYDMvwstpvtHLmcgX?usp=share_link
* Looking at the PDF manual the headphone jack has a mic connector for external micrphone support.

