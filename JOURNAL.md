---
title: "Digital NameTag"
author: "Megan Campbell"
description: "A wearable badge with a QR Code on the case and a digital display to show my name."
created_at: "2024-06-05"
---

Total Time: 7 hours and 15 minutes

June 5: (1 hours)
I came up with the project idea and started working on the schematic. I wanted to include OLED and ESP32 as well as a battery pack. 


June 6: (30 min)
I looked at different ways to hook up the OLED. I have never done this before, so I had to switch out which OLED I was using due to an incompatability issue. 

June 10: (45 min) 
I finished the schematic and tried to make the PCB. I had a really hard time with the routing. I don't know why I can't route on both sides. If I don't, I am having a lot of errors with overlap of tracks. I watched a lot of YouTube videos but I couldn't figure it out. 
[UntitledSchematic.pdf](https://github.com/user-attachments/files/20933656/UntitledSchematic.pdf)


June 12: (1 hour) 
I rearranged the entire PCB because my routing still isn't working. I went back to my schematic and tried to use smaller components. I still don't know why I can't route it. I tried several times to do different configurations/combinations. 

June 17: (1 hour) 
I figured out that I can't route components that are on one side on the back of the board unless there are yellow circles on the PCB. Using this knowledge, I finished the PCB. 

<img width="675" alt="Screenshot 2025-06-26 at 10 56 20 PM" src="https://github.com/user-attachments/assets/dc8941f3-0fc1-421f-922a-0759b16f72ff" />


June 19: (20 min) 
I started putting my files together and I made the CAD for the case. I also found a website that converts links to STL files of QR codes which is pretty cool. I used a link to my LinkedIn.
<img width="536" alt="Screenshot 2025-06-26 at 10 58 55 PM" src="https://github.com/user-attachments/assets/aa573855-3179-4df6-841e-e395362266ae" />


June 23: (2 hours)
I lowkey didn't know what I was doing and the CAD looked really stupid, so I decided to completely start over. I am now using an arduino nano because I understand arduino better, a MAX7219 because I like the shape, and two batteries (one 4.5V and one 9V). I made the schematic. I also decided that because I am completely lost on making a PCB I am just going to solder this myself at home. I do still need a CAD but only to hold the batteries. I started working on the CAD by importing a 9V battery model and a 3 AAA case for the 4.5V power source. I also downloaded CAD files for the MAX7219 and the arduino Nano.

June 24: (1 hour) 
I locked in, finished the CAD, schematic, and PCB. I put everything in the GitHub and finally submitted the custon project :D

I also wrote the code in the Arduino IDE and saved it in my GitHub as txt just for my name to scroll across the screen. 


[Badge Schematic.pdf](https://github.com/user-attachments/files/20933722/Badge.Schematic.pdf)

<img width="500" alt="Screenshot 2025-06-26 at 11 01 30 PM" src="https://github.com/user-attachments/assets/2c6571bb-c687-4dcf-a4dc-d878b2d02621" />

July 8: (40 minutes)

For rereview: I added threaded holes to the CAD for the hinge, then I removed the hinge entirely and made screw holes in the bottom of the case.
I added 4x M5x0.8 20mm nails to the BOM
I also updated the BOM and submitted. 

