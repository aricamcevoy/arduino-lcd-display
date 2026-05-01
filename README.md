## Description
Basic Arduino project displaying text on a 16x2 LCD using parallel communication.

## Features
Displays custom text ("Hello World!")
Uses LiquidCrystal library
Adjustable contrast via potentiometer
Hardware
Arduino Mega 2560
16x2 LCD (HD44780)
Potentiometer (contrast control)
Breadboard + jumper wires

## Wiring (important pins)
RS → 7
E → 8
D4–D7 → 9–12
RW → GND ⚠️ (critical fix)
VO → potentiometer middle pin

## Lessons Learned
LCD requires correct RW grounding for write mode
Contrast must be adjusted via potentiometer
Debugging hardware requires verifying both wiring and code

## Issues
Initally encountered issue where LCD powered on but displayed no text due to RW pin not being grounded. Resolved through hardware debugging.
