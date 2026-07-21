# Smart Parking System
Arduino-based Smart Parking System using an HC-SR04 ultrasonic sensor to detect vehicle presence and monitor parking slot availability. The Arduino Uno processes sensor data and displays the slot status as "OCCUPIED" or "EMPTY" on a 16×2 LCD using an I2C module.

Project Title: Smart Parking System

Core idea:
An Arduino-based parking monitoring system that uses an HC-SR04 ultrasonic sensor to detect whether a parking slot is occupied or empty, and displays the status on a 16×2 LCD using an I2C module.

Main Hardware:

Arduino Uno (ATmega328P)
HC-SR04 Ultrasonic Sensor
16×2 LCD Display
I2C LCD Module
TP4056 Charging Module
3.7V Li-ion 18650 Battery
Jumper wires and breadboard

Software:

Arduino IDE
Embedded C / Arduino C++
Serial Monitor

*Report*: [Smart Parking System Report.pdf](https://github.com/user-attachments/files/30239022/Smart.Parking.System.Report.pdf)

<img width="1361" height="688" alt="Circuit Diagram" src="https://github.com/user-attachments/assets/497633ea-e057-43b6-ae11-8b345d5a37f8" />

*Code*: [Code (NotePad).txt](https://github.com/user-attachments/files/30239282/Code.NotePad.txt)

The code currently uses:

TRIG → Pin 9

ECHO → Pin 10

LCD I2C address → 0x27

LCD → 16×2

Occupied condition: distance ≤ 10 cm

Empty condition: distance > 10 cm


The report also discusses future expansion into multiple parking slots, mobile applications, cloud/IoT monitoring, online booking, digital payments, automatic gates, RFID, cameras, and AI-based parking prediction, but the actual implemented prototype described in the report is primarily the Arduino + ultrasonic sensor + LCD system.



