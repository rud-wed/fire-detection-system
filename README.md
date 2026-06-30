# Fire Detection System 🔥

## Overview
A smart fire detection system built with ESP32, MQ-2 gas sensor, IR flame sensor, and DHT11/DHT22 for temperature & humidity.  
Real-time monitoring via 16x2 LCD, buzzer, and LED indicators. Designed for homes, schools, and workplaces.

## Problem Statement
Traditional fire detection systems suffer from delayed response, false alarms, and limited monitoring.  
Our solution integrates multiple sensors with intelligent threshold verification to improve accuracy and reduce false alarms.

## Features
- Smoke & gas detection (MQ-2)
- Flame detection (IR sensor)
- Temperature & humidity monitoring (DHT11/DHT22)
- Real-time LCD display
- Instant buzzer & LED alerts
- Optional cloud integration (ThingSpeak)
- Solar/battery backup for off-grid use

## Hardware Used
- ESP32 Development Board
- MQ-2 Gas Sensor
- IR Flame Sensor
- DHT11/DHT22 Sensor
- 16x2 LCD with I2C
- Passive Buzzer & LEDs
- Breadboard, Jumper Wires, USB/5V DC Power

## System Architecture
1. Initialize sensors, LCD, buzzer.
2. Read MQ-2, IR flame, DHT11/22.
3. If fire detected → activate buzzer + display alert.
4. Else → continue monitoring.
5. Optional: send data to cloud via Wi-Fi.

## Learning Outcomes
- IoT & Embedded Systems
- Sensor Integration
- Circuit Prototyping
- Real-world Safety Applications

## Mentor
Guided by **Ms. G. Brindha, M.E., Assistant Professor**  
Department of AI & DS, Dr. NGP Institute of Technology

## Conclusion
This project demonstrates a cost-effective, scalable fire detection system with quick response and real-time alerts, contributing to improved safety in everyday environments.
