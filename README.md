# Smart IoT Fire Detection and Automatic Sprinkler

Course prototype for Embedded Systems at BINUS University. It demonstrates how an ESP8266 can read sensors, drive a local alarm and water pump, and report status to a mobile dashboard.

## How it works

1. A Wemos D1 reads the flame and temperature sensors.
2. When detection logic triggers, it activates the LED and buzzer and controls the pump and servo.
3. Blynk shows temperature and status, sends alerts and offers manual sprinkler control.

<img width="360" alt="Physical ESP8266 course prototype" src="https://github.com/user-attachments/assets/7fb4fe3c-7295-42ff-abe2-b1a407a5ebff" />

## Prototype and stack

| Layer | Components |
| --- | --- |
| Controller | Wemos D1 / ESP8266 |
| Sensing | Flame sensor and temperature sensor |
| Outputs | Relay, 12 V pump, servo, LEDs and buzzer |
| Software | C++, Arduino IDE, ESP8266 libraries and Blynk IoT |
| Simulation | Wokwi |

The course demonstration covered the sensor-to-actuator workflow, local alerts and Blynk controls. This repository documents an academic prototype.

## Dashboard

<img width="640" alt="Blynk dashboard for monitoring and manual controls" src="https://github.com/user-attachments/assets/af1ce7a4-467a-4449-ae50-51db978f07a0" />

[Project overview image](https://github.com/user-attachments/assets/0516bf51-6c6a-4f3e-b5c3-7a42b5c02457)

## Next steps

Add repeatable checks for sensor triggers and device reconnects, then record readings for reviewing false alarms and missed detections.

## Author

Muhammad Aldo Ghiffari, Computer Science, BINUS University.
