---
layout: page
title: Wayfarer 3 Keypad
permalink: /wayfarer/keypad/
---
# Keypad

## 20 Pin Connector

Arrow is PIN 1 (Notches on this side)

| -V- | --- |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 3   | 5   | 7   | 9   | 11  | 13  | 15  | 17  | 19  |
| 2   | 4   | 6   | 8   | 10  | 12  | 14  | 16  | 18  | 20  |


Pin 1 - COL - SW25 (ISSUE), SW21, SW17, SW4
Pin 2 - Empty
Pin 3 - COL - SW22, SW18, SW14, SW1
PIN 4 - LDR1 (NC)
Pin 5 - ROW - SW21, SW20, SW19, SW18
Pin 6 - LDR1 (NC) Light Dependent Resistor?
Pin 7 - COL - SW3, SW16, SW20, SW24
Pin 8 - Speaker
Pin 9 - COL - SW2, SW15, SW19, SW23
Pin 10 - Speaker
Pin 11 - ROW - SW22, SW23, SW24, SW25, SW26, SW27, SW28, SW29
Pin 12 - COL - SW6, SW27, SW32, SW11
Pin 13 - ROW - SW14, 15, 16, 17, 9, 10, 11, 12
Pin 14 - COL - SW7, 28, 10, 31
Pin 15 - ROW - SW1, 2, 3, 4, 5, 6, 7, 8
Pin 16 - COL - SW8, 9,  29, 30, 13
Pin 17 - COL - SW5, 26, 12, 33, 34
Pin 18 - ROW - SW13, 34
Pin 19 - LED 5v
Pin 20 - LED Ground

## Keys

| Switch | Row | Col | Name           |
| ------ | --- | --- | -------------- |
| 1      | 15  | 3   | 7              |
| 2      | 15  | 9   | 8              |
| 3      | 15  | 7   | 9              |
| 4      | 15  | 1   | Plus           |
| 5      | 15  | 17  | Top 1 Left     |
| 6      | 15  | 12  | Top 2          |
| 7      | 15  | 14  | Top 3          |
| 8      | 15  | 16  | Top 4          |
| 9      | 13  | 16  | Top 5          |
| 10     | 13  | 14  | Top 6          |
| 11     | 13  | 12  | Top 7          |
| 12     | 13  | 17  | Top 8          |
| 13     | 18  | 16  | Top 9 Right    |
| 14     | 13  | 3   | 4              |
| 15     | 13  | 9   | 5              |
| 16     | 13  | 7   | 6              |
| 17     | 13  | 1   | Minus          |
| 18     | 5   | 3   | 1              |
| 19     | 5   | 9   | 2              |
| 20     | 5   | 7   | 3              |
| 21     | 5   | 1   | Down           |
| 22     | 11  | 3   | C              |
| 23     | 11  | 9   | 0              |
| 24     | 11  | 7   | Issue          |
| 25     | 11  | 1   | Issue          |
| 26     | 11  | 17  | Bottom 1 Left  |
| 27     | 11  | 12  | Bottom 2       |
| 28     | 11  | 14  | Bottom 3       |
| 29     | 11  | 16  | Bottom 4       |
| 30     | 5   | 16  | Bottom 5       |
| 31     | 5   | 14  | Bottom 6       |
| 32     | 5   | 12  | Bottom 7       |
| 33     | 5   | 17  | Bottom 8       |
| 34     | 18  | 17  | Bottom 9 Right |

## Speaker

Connected to Pin 8 & 10 of the keyboard connector.

Can be driven with 3.3v. The polarity doesn't matter.
It is a muRata Passive Buzzer or Piezo Speaker.

## Keypad LEDs

Each switch has a green LED (34 in total)
Each label has a green LED (2 rows x 9 labels = 18)
Total = 52 leds

The LEDs are paired in series with 26 parallel lines.

The voltage drop measured across a LED was 1.8v.

![LED Volt Drop](/assets/WF3 - LED V Drop.png)