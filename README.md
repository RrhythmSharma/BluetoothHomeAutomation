# Bluetooth-Home-Automation

### Description
A solution to control home appliances using a Bluetooth device(Android Smartphone).

This repository consists of source code for an Android app as well as 8051 microcontroller code.

### Requirements
1. 8051 microcontroller
2. HC-05 or HC-06 Bluetooth Module
3. 5V DC / 220V AC Relays
4. Android Bluetooth Device
5. Connecting Wires

### Steps to setup Arduino
* Upload the arduin code in repository root to Arduino controller
* Connect PIN 11(TX) pin of Arduino to RX pin of HC-05
* Connect PIN 10(RX) pin of Arduino to TX pin of HC-05
* Connect 5V of Arduino to V<sub>in</sub> of HC-05 and V<sub>cc</sub> of relays
* Connect GND of Arduino to GND of HC-05 and GND of relays
* Connect IN of relay to PIN 13 of Arduino board(you are free to use any pin and also multiple pins, just update the arduino code)
* Connect 220V AC Line to Pole and Load(appliance) to NO of the relay
* Power the Arduino board and you're ready to use. Refer to circuit diagram for setup

### How to use
* Build an install the app on an Android Bluetooth device.
* Turn Bluetooth ON and pair with HC-05 using passcode 1234 (default passcode, you are free to change)
* Open the app, click on select conntroller and select the HC-05
* Use ON/OFF buttons to control the appliance

### Purpose
Mini Project for Bachelor of Technology, Rajasthan Technical University, Rajasthan.

### Developed by
Rhythm Sharma



