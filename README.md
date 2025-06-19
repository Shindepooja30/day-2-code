# Servo Angle Control with Arduino Uno

## Overview

This project demonstrates how to control an **SG92R micro servo motor** using an **Arduino Uno**. The servo angle is adjusted in real-time based on user input through the **Serial Monitor** in the Arduino IDE.

## Components Used

* Arduino Uno
* SG92R Micro Servo
* USB Cable
* Jumper Wires
* External 5V Power Supply (recommended for stable servo performance)

## Features

* Controls servo angle from 0° to 180°
* Accepts angle input via Serial Monitor
* Uses Arduino's built-in `Servo` library

## How It Works

1. User enters a value (0–180) in the Serial Monitor.
2. Arduino reads this value and moves the servo to the corresponding angle using PWM.
3. The servo responds immediately, allowing real-time testing and control.

## Setup Instructions

1. Connect the SG92R servo:

   * Red wire → 5V
   * Brown wire → GND
   * Orange wire → Digital Pin 9 (PWM pin)
2. Upload the Arduino code using Arduino IDE.
3. Open the Serial Monitor, set baud rate to 9600, and input angles between 0 and 180.
