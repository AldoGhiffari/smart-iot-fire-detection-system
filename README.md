# 🔥 Smart IoT Fire Detection & Automatic Sprayer System

<img width="599" height="457" alt="Screenshot 2026-07-13 at 13 59 45" src="https://github.com/user-attachments/assets/0516bf51-6c6a-4f3e-b5c3-7a42b5c02457" />


> An embedded IoT-based fire detection system that automatically detects fire, sends real-time alerts, and activates a water sprayer to suppress flames. Developed as a final project for the Embedded Systems course at BINUS University.

---

# 📖 Project Overview

Traditional fire detection systems typically rely on alarms that require manual intervention. This project enhances fire safety by integrating automatic fire detection, real-time monitoring, and an automatic water sprayer into a single embedded system.

The system continuously monitors environmental conditions using flame and temperature sensors. Once a fire is detected, it immediately activates visual and audio alarms, sends a notification through the Blynk IoT platform, and automatically turns on a water pump to spray water toward the fire source.

This project demonstrates the integration of embedded systems, IoT communication, sensor technology, and automation for smart safety applications.

---

# ✨ Features

- 🔥 Real-time flame detection
- 🌡 Temperature monitoring
- 💧 Automatic water pump activation
- 📱 Remote monitoring using Blynk IoT
- 🔔 Buzzer alarm notification
- 🚨 LED status indicators
- 📡 Wi-Fi communication
- 🎮 Manual control from mobile application
- ⚡ Low-cost embedded implementation

---

# 🛠 Hardware Components

| Component | Function |
|-----------|----------|
| Wemos D1 (ESP8266) | Main microcontroller |
| Flame Sensor | Detects fire |
| Temperature Sensor | Measures temperature |
| Servo Motor | Controls sprinkler direction |
| 12V Water Pump | Sprays water |
| Relay Module | Controls pump power |
| LED Indicators | Displays system status |
| Buzzer | Audible warning |
| Wi-Fi | IoT communication |

---

# 💻 Software Stack

- Arduino IDE
- C++
- ESP8266 Libraries
- Blynk IoT
- Wokwi Simulator
- GitHub

---

# 🏗 System Architecture

The system consists of flame and temperature sensors connected to an ESP8266 microcontroller. Sensor readings are processed in real time to determine whether fire conditions are detected. When triggered, the ESP8266 activates the relay, water pump, servo motor, LED indicators, buzzer, and sends notifications to the Blynk mobile application through Wi-Fi.

---

# 🔄 System Workflow

System workflow:

1. Monitor flame and temperature sensors.
2. Read sensor values continuously.
3. Detect abnormal fire conditions.
4. Activate buzzer and warning LEDs.
5. Send notification to Blynk.
6. Turn on water pump.
7. Rotate servo toward fire direction.
8. Continue monitoring until the fire is cleared.

---

# 📷 Prototype

<img width="4284" height="5712" alt="IMG_4209" src="https://github.com/user-attachments/assets/7fb4fe3c-7295-42ff-abe2-b1a407a5ebff" />


Physical prototype built using:

- ESP8266 Wemos D1
- Flame Sensor
- Temperature Sensor
- Relay Module
- Water Pump
- Servo Motor
- Breadboard Prototype

---

# 📱 IoT Dashboard

<img width="848" height="448" alt="Screenshot 2026-07-13 at 14 06 56" src="https://github.com/user-attachments/assets/af1ce7a4-467a-4449-ae50-51db978f07a0" />


The Blynk dashboard enables users to:

- Monitor fire detection status
- View temperature values
- Receive real-time notifications
- Control the sprinkler manually
- Monitor system operation remotely

---

# 💻 Source Code

The source code is written using Arduino C++ and organized around several functional modules:

- Sensor Reading
- Fire Detection Logic
- Pump Control
- Servo Control
- Notification System
- Blynk Communication

Future versions may separate these modules into dedicated source files for improved maintainability.

---

# 🚀 Getting Started

## Requirements

- Arduino IDE
- ESP8266 Board Package
- Blynk Library
- USB Cable
- Wemos D1 ESP8266

## Installation

1. Clone this repository.
2. Open the project in Arduino IDE.
3. Install the required libraries.
4. Configure your Wi-Fi credentials and Blynk authentication token.
5. Upload the program to the ESP8266.
6. Connect all hardware components.
7. Power the system and begin monitoring.

---

# 📊 Results

The prototype successfully demonstrated:

- Successful flame detection
- Temperature monitoring
- Automatic sprinkler activation
- Water pump control
- Real-time mobile notifications
- Remote monitoring via Blynk
- Reliable embedded system integration

---

# 🔮 Future Improvements

Future development may include:

- Smoke sensor integration
- Gas leak detection module
- AI-based fire classification
- Camera-based monitoring
- Cloud database logging
- Battery backup system
- Solar-powered deployment
- Mobile application redesign
- Multiple sensor zones
- Emergency service integration

---

# 📚 References

- Arduino Documentation
- ESP8266 Documentation
- Blynk IoT Documentation
- Wokwi Simulator
- Fire Detection and Automatic Suppression System research papers

---

# 👨‍💻 Author

**Muhammad Aldo Ghiffari**

Computer Science — BINUS University

Areas of Interest:

- Embedded Systems
- Internet of Things (IoT)
- Python Development
- Intelligent Systems
- Software Engineering

---
