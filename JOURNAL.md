---
title: "QuFi Hackclub Project Day 1"
author: "Darsh Shah"
description: "Working on creating a macropad to simplyify gaap accounting on excel"
created_at: "2026-011-01"
---

# November 1: Designed the Schematics layout

Worked on creating a matrix schematic for my macropad on Kicad and succesfuly created the schematic
and the connections.

![Schematics version 1](Images_QuFI/Schematics_Day1.png)

**Total time spent: 1.5 hours**

# November 2: Designed the PCB layout

Worked on creating a PCB for my macropad on Kicad and added a rotary encoder components. A big time crunch today was making sure that my 
3dshapes paths were correct. This is my first time working on schematics and with the tutorial i'm watching of ScottoKeebs I ran into issues with pulling few 
3d models but after a few hours of troubleshooting I got it!

![pcb layout version 1](Images_QuFI/PCB_Day2.png)

**Total time spent: 1.5 hours**

# November 3: Improve the schematics and added components

I realized yesterday(Nov 2) that I don't want to stick to just switches and rotary encoder. I want to add more features like led backlights to represent the 
command layer, or just for customization. I also wanted to add the oled display to display things features such as command layer, function choosen, or etc(the
full ideas for oled are still jogging through my mind for me to chase, lol). So I ended up watching a few videos, ton of google searches, and some questions for gemini
to figure out how voltage works for these additional components, expanding pins available, making sure the electrical properties are working correctly, 
and that the schematics is also simplified. In the end I added all my components and simplified the schematic to the best of my current ability. The components added 
include 16 mini e leds, I/O expansion, and a 128 by 32 pixel OLED display

![pcb layout version 1](Images_QuFI/Schematics_Day3.png)

**Total time spent: 1.5 hours**

# November 4: Simplify Schematics and Adjust NETS, POWER, and VOLTAGE

Bascially when I opened up my schematics today to check if everything is good for the get go on the PCB, I realized something. The schematics could be describe as modern "art",
so I committed myself to somewhat cleaning up this eyesore with the little I know about schematics so far and some help of gemini to figure out how to quickly apply changes onto multiple
components. In doing so ended up creating nets for most things, I also just simplified power connections with labels and pwoer flags. I also added a ton of capacitors to make sure the LED
colors were more consistant.

![pcb layout version 1](Images_QuFI/Schematics_Day4.png)

**Total time spent: 1.5 hours**

# November 5: Re-Arranging PCB

I honestly did not have any time today to do anything so I just went on for ten minutes and moved a few things around on the PCB and planned 
how I will move more stuff when I get the time.
![pcb layout version 1](Images_QuFI/PCB_Day5.png)
**Total time spent: 0.16 hours**

# November 6: Continuation of PCB organization

I continued what I started the previous day which was the organization of all the components on the PCB before I get to routing. I mostly got everything completed except for capciotrs and resistors
which I will soon hopefully work on. I changed some footprints and layered some components on top of eachother. Lots of off camera research for me to undestand if its possible. Also I tried to make my own footprint 
which didn't go to well but I think I know how to do it if I need it in the future.

![pcb layout version 1](Images_QuFI/PCB_Day6.png)

**Total time spent: 2.15 hours**

# November 7-8: More organization and routing traces

These two days I just pretty much did a tad bit of finalizing on where I wanted to place all the components on the board relative to routing and etc. I ended up routing mostly everything and had to watch a few videos on that.
I also had to learn how to make pour zones and other types of zones. I ended up doing a copper pour for my GND and just made a zone so that I don't have to individually trace it. I also did no pour zones so that some pads don't short 
circut the board. 

![pcb layout version 1](Images_QuFI/PCB_Day7.png)
![pcb layout version 1](Images_QuFI/PCB_Day8.png)
**Total time spent: 4.5 hours**

# November 9: Fixing everything on DRC and getting 3d model ready

Today I did the DRC and started debugging everything that had any conflcits. My main problems were some edge cuts and holes in my led footprints that I have no purpose for. So I ended up universally changing those footprints to a new edited
version I made. I also added some m2 screw holes around the board for me to properly screw it into the frame.

![pcb layout version 1](Images_QuFI/PCB_Day9.png)

**Total time spent: 1.5 hours**

# November 10-12.: 3d modeling, PCB Edits, and CAD

Genuinely a terrible attempt at CAD today. I redownloaded fusion 360 after a few years and I imported the step file for my PCB. Turns out instead of a step file I needed an OBJ or  just a normal 3d file to simplify
manipulation. Once I got that figure out I started designing the casing but then I realized my edge cuts for the PCB were genuinly random measurments so i had to edit the PCB so it can be an actual dimensioned rectangle. 
Once I had the new file I created a rough case and some mounting pads for the PCB.

![pcb layout version 1](Images_QuFI/CAD_Day10-12.png)

**Total time spent: 3 hours**

# November 14-15.: Fixing everything on DRC and getting 3d model ready

A much more noble attempt at designing the 3d housing for the PCB. I ended up starting off with making the USB C hole. I then added holes to the PCb pads to screw it in with the actual PCB.
I continued then to add screws connecting a bottom piece to the top, however, I realized that the top piece and the PCB pads made it impossible to put in a bottom layer if I wanted to. So I made a new 
version with the same features but I joined the triangular PCB pads to the bottom. I then made the top its own cap with heatset insert holes, and the bottom has a securing hole for m2 screws. Another noticable
issue I found was that the casing was disproportionate and the left side had more space from the keys that the right side. This is not really a huge design issue but it can irrirtate some people and might make hand placement
difficult. So I edited the bottom and top part to be uniform with the board and keys.

![pcb layout version 1](Images_QuFI/CAD_Day14-15.png)

**Total time spent: 4.5 hours**
