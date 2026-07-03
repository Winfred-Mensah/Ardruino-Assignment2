# Arduino-Assignment2 - Beeping Countdown

This is my submission for Assignment 2 in the Programming C++ for Engineers Using Arduino course at Ghana Communucations Technology University(GCTU).

## What this project does

A 7-segment display counts doen from 9 to 10. On each step, a passive buzzer plays a short beep. When the countdown reaches 0, the buzzer plays a longer tone to signal completion.

## Hardware used

- Arduino Uno
- 1 x passive buzzer (piezo)
- 1 x single-digit 7-segment display (common cathode)
- 1 x 220 ohm resistor (on the COM pin)
- Breadboard and jumper wires

## Concepts demonstrated

- The tone() and noTone() functons
- Passive vs active buzzers
- 7-segment display wiring (common cathode)
- 2D arrays for digit patterns (lookup table)
- Functions with parameters
- while and for looops
- Serial Monitor output

## How to run it

1. Wire the buzzer to pin 8.
2. Wire the 7-segments a-g to Arduino pins 2, 3, 4, 5, 6, 7,9 (direct wires, no resistors).
3. Connect the COM pin of display to GND via a 220 ohm resistor.
4. Open the .ino file in the Arduino IDE.
5. Select Tools > Board > Arduino Uno and correct Port.
6. Click Upload.

## Author

MENSAH WINFRED SOWAH - 2526402217

