---
layout: post
title:  "Wayfarer 3 Front Panel Testing"
date:   2021-05-03 16:30:00 +0100
categories: wayfarer3
---
One of the first things I wanted to do was test the LCD panel and keypad using a Raspberry Pi Pico. The keypad is arranged in a matrix and the LCD is a Optrex PWB16188A which seems to be a DMC-16188. The LCD uses a Hitachi HD44780 controller which luckily is fairly common for LCDs. The LCD can display one line with 16 characters, each character is 5x8. There is also a piezo speaker in the middle of the keypad and a space for a light dependent resistor (LDR).

![WF3 Back of LCD and Keypad](/assets/WF3 - LCD Chips.png)

The keypad was easy to work out with a multimeter and you can find the pin out on [this page]({% link wayfarer/keypad.md %}).

The LCD should have been easy too, after working out that it was equivalent to the DMC-16188, I managed to find the [datasheet here](). The only problem I had with the screen was that Pin 1 on the connector (marked with an arrow) was not equivalent to Pin 1 on the LCD; in fact it was Pin 2.

Unfortunately I didn't have a 100k potentiometer to hand either so had to deal with the bad contrast too.

![WF3 Back of LCD and Keypad](/assets/WF3 - LCD Test.png)

Details on all the above can be found here:
- [LCD Page]({% link wayfarer/lcd.md %})