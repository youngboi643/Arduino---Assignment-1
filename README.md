# Arduino Assignment 1 - Smart Countdown
This is my submission for Assignment 1 in the Programming C++ for Engineers Using Arduino course at Ghana Communication Technology University(GCTU).

## What this program does
It counts down from 5 to 1 using a while loop. On each step:
- It prints "Count: N" to the Serial Monitor.
- It blinks the on-board LED N times using a function called flashLED().

when the countdown finishes, it prints "=== Countdown Complete ===".

## Concepts demonstrated
- Variables (int)
- Functions with parameters (flashLED)
- The while loop
- Digital output (digitalWrite, pinMode)
- The Serial Monitor (Serial.begin, Serial.print, Serial.println)

## Note
This was developed and tested using the Wokwi online Arduino simulator, since I did not have access to a physical Arduino kit

## How to run it
1. Open the .ino file in the Arduino IDE, or paste it into a new Wokwi project.
2. If using real hardware: connect an Arduino Uno via USB, select Tools > Board > Arduino Uno and the correct port, then Upload.
3. Open the Serial Monitor (9600 baud) to see the countdown output.

## Author
Ethan Ewoenam Anyigbanua - 2526401481
