# Smart Home Security System with Keypad Access and Gas Leak Detection via GSM
----
## Overview
This project is an Arduino-based closed-loop system combining home security and gas leak detection.

It uses:
- Keypad for password access
- MQ-2 sensor for gas detection
- GSM module for SMS alerts
- Automatic door unlock during emergencies

---

## Components

- Arduino Uno
- MQ-2 Gas Sensor
- 4x4 Keypad
- Servo Motor
- Relay Module
- Buzzer
- LCD (16x2 I2C)
- SIM800L GSM Module
---
## Features

### Security
- Password-based access
- 3 wrong attempts → system lock + SMS alert

### Gas Detection
- Detects LPG, smoke, methane
- Activates alarm 

### Emergency Response
- Automatically unlocks door during gas leak
