This is a custom front half of the OPI5 shell that has a universal insert located in the 45 degree area of the case. There is a blank filler and one that uses the i2c LCD. The lcd designed for is this one https://www.amazon.com/dp/B076WXR8N9 "i2c OLED Display 0.96 Inch" The pinout is part of the cad drawing.
The blank filler can be modified for anything custom, I did design the filler with the idea of using brass thread inserts with 2.5mm screws.

There is a CR2032 battery holder location. This is designed for a ******* real ******* vertical pcb mount battery holder as pictured.
![opi5 micro desktop rtc battery](https://user-images.githubusercontent.com/15570512/219877684-f7669b34-cb19-457a-9a69-04a5aa293ff8.jpg)

![5a1bccd3-be66-45ea-b0ee-86c1367f1945](https://user-images.githubusercontent.com/15570512/219877354-94cb92fd-8aff-47c6-b133-5b46d7c69e46.jpg)
The idea is to feed the fine wires through the hole as pictured.![opi5 micro desktop rtc battery wire hole at base](https://user-images.githubusercontent.com/15570512/219877693-59dbb727-9029-4a40-9e68-f02d67c2c513.jpg)


Then solder the wires to a "KEYED JST" connector so its not able to be plugged in backwards. With out using a jst connector or like connector, the OPI5 would be hard wired to the RTC battery and can not be removed from the case. There are two test pads on the back of the OPI5 for RTC. One is labled "RTC" for +3v cr2032 power and the other is labled "GRD" DO NOT MIX THESE UP! Wires soldered to these tiny points should be strain reliefed with hotglue or epoxy dots and zip tie the wires to the OPI5 standoffs. In the picture below you can see the RTC and GND test pads on the back side of the OPI5 with a red arrow pointing at them.

![pi-5-bottom-view](https://user-images.githubusercontent.com/15570512/219877982-a21b246d-de2f-414f-8482-af740ac2db17.png)
