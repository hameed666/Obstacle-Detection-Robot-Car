# Obstacle Detection and Avoiding Robot Car Using Arduino UNO

## Project Overview

This project was developed during my Diploma in Electrical and Electronics Engineering to understand the fundamentals of embedded systems and robotics. The robot is capable of detecting obstacles using an HC-SR04 ultrasonic sensor and automatically changing its direction to avoid collisions.

The complete system is built around an Arduino UNO microcontroller, which continuously processes the sensor data and controls the movement of the DC motors through an L293D motor driver.

---

## Features

- Automatic obstacle detection
- Autonomous obstacle avoidance
- Ultrasonic distance measurement
- Servo motor based scanning
- Battery powered operation
- Arduino UNO based controller

---

## Hardware Used

- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- L293D Motor Driver
- DC Motors
- Rechargeable Battery
- Robot Chassis

---

## Software Used

- Embedded C
- Arduino IDE
- ExpressSCH (for circuit design)

---

## How the Robot Works

1. The ultrasonic sensor continuously measures the distance in front of the robot.
2. The sensor is mounted on a servo motor to scan different directions.
3. If an obstacle is detected, the Arduino checks the available path.
4. The motor driver changes the direction of the DC motors.
5. The robot continues moving through the obstacle-free path.

---

## Block Diagram

![Block Diagram](BlockDiagram.png)

The block diagram shows the connection between the Arduino UNO, ultrasonic sensor, servo motor, motor driver and DC motors.

---

## Circuit Diagram

![Circuit Diagram](SchematicDiagram.png)

The schematic illustrates the interfacing of the Arduino UNO with the ultrasonic sensor, servo motor and L293D motor driver.

---

## Project Outcome

The robot was successfully able to detect nearby obstacles and automatically avoid them without manual intervention. The project helped me understand sensor interfacing, embedded C programming, motor control and hardware integration using Arduino.

---

## What I Learned

During this project I gained practical experience in:

- Arduino Programming
- Embedded C
- Ultrasonic Sensor Interfacing
- Motor Driver Control
- Servo Motor Control
- Embedded Systems
- Basic Robotics
- Hardware Troubleshooting

---

## Achievement

🏆 **2nd Prize – Telangana State Srujana Techfest (2023–2024)**

This project received the State Level Second Prize during Telangana State Srujana Techfest for its practical implementation of an autonomous obstacle detection and avoidance robot.

---

## Future Improvements

Some features that can be added in future versions are:

- Bluetooth Control
- Mobile App Control
- Wi-Fi Monitoring
- Camera Based Navigation
- AI Object Detection
- GPS Navigation

---

## Repository Contents

```text
├── README.md
├── LICENSE
├── Arduino_Code
├── Documentation
├── BlockDiagram.png
└── SchematicDiagram.png
```

---

## Author

**Mohammed Hameed**

Diploma in Electrical and Electronics Engineering

**Areas of Interest**

- Electric Vehicles
- Embedded Systems
- Robotics
- Power Electronics
- MATLAB/Simulink

---
