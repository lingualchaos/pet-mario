# Smart Pet Gate System
An Embedded Systems Hardware Project

## Project Summary

Interfacing an IR sensor with an Arduino Uno to detect the presence of your pet. Upon detection of your pet i.e. obstacle, gate opens for 3 seconds, simultaneously a notification is sent on your phone through Bluetooth, the gate closes back using a servo motor and the corresponding LED lights up.

The Smart Pet Gate System provides a practical solution for pet owners, ensuring their pets' safe and convenient movement in and out of the house. By integrating various hardware components and programming them using the Arduino platform, this project demonstrates the potential of embedded systems in solving everyday problems. Future enhancements could include implementing additional features such as remote control functionality, pet identification, and access logging.

## Code Overview

The Smart Pet Gate System consists of an Arduino Uno microcontroller board interfaced with various components, including an IR sensor, a servo motor, LEDs, a piezo buzzer, and a Bluetooth module. The IR sensor is used to detect the presence of the pet near the gate. Once the pet is detected, the system initiates the following sequence of events:
1.	The piezo buzzer plays the iconic Super Mario melody to alert the pet owner.
2.	At the same time, a notification is sent to the pet owner's smartphone via Bluetooth saying: “Pet Detected!”
3.	The servo motor rotates to open the gate, allowing the pet to pass through, and the pet owner is notified: “Gate Opened!”
4.	After a predetermined time, the gate closes automatically.
5.	LEDs indicate the gate's open and closed states. 

