# SmartBin

Arduino-Based Automatic Touchless Waste Management System

## Overview
SmartBin is an embedded systems mini project that automatically opens a dustbin lid using an ultrasonic sensor and servo motor. It reduces physical contact and improves hygiene.

## Features
- Touchless lid operation
- Ultrasonic distance sensing
- Automatic open/close mechanism
- Low-cost hardware
- Easy to build

## Hardware Components
- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- Servo Motor (SG90)
- Jumper Wires
- 9V Battery / USB Power

## Circuit Connections

Ultrasonic Sensor
- VCC → 5V
- GND → GND
- Trig → D9
- Echo → D10

Servo Motor
- Signal → D11
- VCC → 5V
- GND → GND

## Working Principle
1. Sensor measures distance
2. If object detected within range
3. Arduino rotates servo to open lid
4. After delay, lid closes automatically

## How to Run
1. Install Arduino IDE
2. Open code/SmartBin_Code/SmartBin_Code.ino
3. Select Arduino UNO
4. Upload code
5. Power the circuit

## Applications
- Homes
- Hospitals
- Offices
- Public places

## Author
nithinxdx ,
Electronics & Communication Engineering
