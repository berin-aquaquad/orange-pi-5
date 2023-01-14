# orange-pi-5
![opi5 micro desktop back and side view](https://user-images.githubusercontent.com/15570512/210899034-5617d4ca-1f99-4545-9630-c1aaf9792690.jpg)

![opi5 micro desktop heatsink standoff mount bracket](https://user-images.githubusercontent.com/15570512/212485847-4f845119-6474-4ce0-8fec-bec8516d64f3.jpg)



OPI5 open micro desktop case design.

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

