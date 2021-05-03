---
layout: post
title:  "Wayfarer 3 Teardown"
date:   2021-04-30 09:15:00 +0100
categories: wayfarer3
---
This is my first post on the Wayfarer 3! A bus ticket machine that is over 30 years old. It cost £20 from eBay and plan I to get it working again keeping the body, LCD, keypad and printer. I will modernize the internals so that I can customize it's functionality.

The first step was to crack open the machine to see what was inside, it was covered in dust everywhere...
![WF3 Dirty Boards](/assets/WF3 - Boards Dirty.png)

Here is the panel behind the keyboard:
![WF3 Behind Keypad](/assets/WF3 - Behind Keypad.png)

This is the leaking battery which I have now removed from the board:
![WF3 Leaking Battery](/assets/WF3 - Battery.png)

The EPROM:
![WF3 EPROM](/assets/WF3 - EPROM.png)

The processor:
![WF3 Processor](/assets/WF3 - Processor.png)

The keypad and LCD screen:
![WF3 Back of LCD and Keypad](/assets/WF3 - Keypad LCD Back.png)
![WF3 Keypad Layout](/assets/WF3 - Keypad Layout.png)
![WF3 LCD](/assets/WF3 - LCD Chips.png)

They are connected to the board with a two ribbon cables, backlight connector and the other cable is for the hole punch.
![WF3 LCD](/assets/WF3 - Main Connectors.png)

The Wayfarer 3 uses a RFID module to load the routes and store data, here is the board:
![WF3 LCD](/assets/WF3 - Module Circuit.png)

The dot-matrix printer:
![WF3 Underneath the Printer](/assets/WF3 - Printer Bottom.png)