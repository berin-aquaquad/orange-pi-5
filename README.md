# ORANGE-PI-5       All cad adjustments should be done and all files I believe have been updated to the git that needed to be. Some how the OPI5 motherboard in the cad drawing was 5mm too long and that displaced everything. The OPI5 motherboard is 62mm x 100mm. I had it as 105mm, so when I made the bracket I had to drill the holes a bit. And I thought I was having a problem with my cnc machine loosing STEPS trying to cut steel. Everything should be accurate if not please message me with an issue, or on armbian opi5 forum.
#                                      KEEP CHECKING BACK I UPDATE THIS GIT REPO OFTEN.
#              FIRST OPI5 IN THE WORLD WITH A REAL MOUNTED ICE TOWER HEATSINK! Now that my OPI5 has a full suite of heatsinks on it. My next focus is on starting the build of the micro desktop case and OS. I believe the first part I'll build is the SBC mounting plane. That will give me something to mount to then I'll start the main body 3d print.

![20230117_181448](https://user-images.githubusercontent.com/15570512/213040467-bef33e19-85ca-407a-9efc-6b4d8a62f26c.jpg)

![opi5 micro desktop back and side view](https://user-images.githubusercontent.com/15570512/210899034-5617d4ca-1f99-4545-9630-c1aaf9792690.jpg)

![opi5 micro desktop heatsink standoff mount bracket](https://user-images.githubusercontent.com/15570512/212485847-4f845119-6474-4ce0-8fec-bec8516d64f3.jpg)

![opi5 micro desktop dimensions](https://user-images.githubusercontent.com/15570512/217111812-a268338b-6934-4fed-9422-e6e85f88a825.jpg)
The core body is 68mm wide. The lower standoffs are 6mm, the upper standoffs are 10mm

![opi5 mounted to plane](https://user-images.githubusercontent.com/15570512/215288946-a3bde6f3-7f01-4628-99d5-ae7febb5b7f5.jpg)


OPI5 open micro desktop case design, with a split body for two options. Main feature printable on smaller cnc machines, second feature is the ablity to have custom front and back desgined panels. Some may need ports on the back of the shell. Other people may desire features like lcd(s) and headers that are on the back to be on the front. Its a more useful design.

2/6/2023 CAD files have been updated and uploaded, unless I missed something everything be updated corrected with the latest corrections. .rsdoc .stl .dxf files and some images have been updated.

2/5/2023 I have milled the corrected back plane and it came out perfect see too pictures when I get to posting. Also I just discovered I made a small not error but over site. One of the back plane mounts is in the wrong location so you can not remove the back plane with the opi5 mounted IF that screw is populated. Because it is under the opi5 board under the stacked USB ports. I'm updating the cad drawing and I'll post the correction some time soon. That will be a correction to the master .RSDOC cad file, and to the back plane DXF file and the back half of the micro desktop tower shell dxf and .rsdoc files when I finish the correction. Look for all 3 files to have the same time date update when updated.

2/4/2023 I have ordered a (https://www.amazon.com/gp/product/B076WXR8N9 "I2c OLED Display 0.96") and I just ordered a new much larger 3d printer. I will be making a custom front shell half version when I get the display. Again this case design is a modular setup so it can be custom to one's needs for the front and back halfs. As well as the width can be adjusted as desired.

2/3/2023 I have finally cut the side covers out of acrylic, I have posted the updated DXF files in the gcode folder as well as posting an image.

1/28/2023 Family visiting and other events and work sorry been quiet for a while. I have just finished a bunch of updates to the cad draws. Fine tuning to the measurements for the heatsink bracket and the mount plane hole spacing for the OPI5, and the mount hole placement of the OPI5 board its self. Sadly I can not find a picture with a measurements breakdown of the opi5 mounting holes. I have milled the back plane but the holes are just off by a hair, it looks good though.

1/22/2023 late tonight. I just updated the the cad files to fully realize the dimentions of the standoffs and other aspects. The CAD drawing should be a first version final draft as of now. The core body has been made a little wider. The core 3D printed body is now 68mm's wide. It was 62mms before getting the replacement standoffs. This also means the placements of the port openings for the OPI5 on the back of the case have been relocated by a few MM as well. JUST A REMINDER this case design is special. The shell is a split body for two reasons, different versions of the front and back halfs of the core micro desktop can be created. And the full sized case can be printed on smaller footprint 3d printers as small as a 110mm x 110mm print area.

1/22/2023 12:30pm ? I have done nothing I just tried turning the opi5 on one last time and it just randomly posted.... I am so confused right now I have done nothing changed nothing. I just plugged it in and it just posted and booted into the SD card ubuntu build???? WTF.... Odd thing is I'm getting no HDMI video but I am getting usbc-hdmi.... Well these problems have destoryed my chance to get anything done this weekend. To much time lost to total failure. About 2 hours after I stopped trying to turn it on, I came back to it and just plugged it in. The red light came on and it just started booting. I DONT GET IT.

* 1/22/2023 I have been endlessly overwhelmed by my employer. I was planning on starting to build parts for the case yesterday 1/21 SAT., but I was tasked with 
* designing and 3d printing. Inclusion mold parts for a many millions of dollars luxury yacht. That being said I just got a chance to test my opi5 today sunday. And I * apear to have a DOA dead unit out of the box. As of this moment this project is on hold indefinitely until I get a working OPI5. I am very angry and very pissed off. * My unit will not power on period, no signs of life nothing. Its 100% dead out of the box.

1/21/2023 I will be cutting the acrylic panel(s) today starting with the SBC mount panel first. I have not cut 1/8th acrylic on my cnc before so I may run into a bit of trial and error figuring the best milling bits out feeds/speeds.

1/16/2023 Ok looking for feed back https://www.amazon.com/Duttek-Degree-Extension-Motorcycle-Dashboard/dp/B08RRYMXB6 https://www.amazon.com/Poyiccot-Extension-Female-Extender-Straight/dp/B086YBP5VW Two examples of USB-C adapter which do you guys like? also USB-c to the front or back of the micro case? 
*************** This is the spacer/stand off kit I have purchased https://www.amazon.com/dp/B08DMSNB8X This is the kit for mounting the OPI5. All spacings will be based off of these when I get them. stay tuned. 6mm and 10mm standoffs are used from this kit. As well as one of the screws with two plastic nuts for holding the m.2 NVME drive.

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

