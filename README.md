
# Servo Motor Control with Arduino

## Project Overview
This project controls a single servo motor using an Arduino board. The servo motor will perform a sweeping motion, moving from 0° to 180° for 2 seconds, and then hold its position at 90° indefinitely. This is a simple demonstration of servo control using the Arduino Servo library.


## Components Needed
- Arduino board (e.g., Arduino Uno)
- 6 Servo motor
- Jumper wires
- Power source for the Arduino (e.g., USB cable)

## Wiring Diagram
- **Servo Motor**: Connect the servo motor’s signal pin to pin 9 on the Arduino, the power pin to 5V, and the ground pin to GND ( As you see in the pecture )
![photo_٢٠٢٥-٠٢-١٤_١٤-٥٩-١٥](https://github.com/user-attachments/assets/10cd443f-6ae7-401f-8669-b8da48bc5cf6)

## Code 
You can get the code by following this pecture and it is provided in the servo code file 
![لقطة شاشة 2025-02-14 145108](https://github.com/user-attachments/assets/e08a9d14-0e89-48e7-9aeb-fc0b41cf32cb)



## How It Works
1. **Setup**: In the `setup()` function, the servo motor is attached to pin 9 of the Arduino.
2. **Servo Sweep**: The servo is commanded to move from 0° to 180° with a small delay to allow the servo to reach each position.
3. **Wait for 2 Seconds**: After completing the sweep, the program pauses for 2 seconds.
4. **Hold at 90°**: The servo is then set to 90°, and the program enters an infinite loop to keep the servo at this position indefinitely.


## Usage
1. Upload the code to your Arduino board using the Arduino IDE.
2. The servo will start sweeping as soon as the program starts running.
3. After 2 seconds, the servo will hold at a 90° position
4. We will make these instructions for all the 6 motors 
