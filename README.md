# Obsticle-Detector-Roboat
## Autonomous Obstacle-Avoiding Robot
An intelligent, self-navigating mobile robot built with Arduino. This project utilizes a triple-sensor ultrasonic array to detect environmental hazards and autonomously navigate through complex paths without human intervention.

### 🚀 Project Overview
This robot mimics basic biological navigation by constantly "scanning" its surroundings. Unlike standard single-sensor builds, this version uses three HC-SR04 sensors (Front, Left, and Right) to eliminate blind spots and provide a 180-degree field of awareness.

The system operates on a Sense-Think-Act logic loop:

Sense: Measures distances in three directions using ultrasonic pulses.

Think: Processes data via the NewPing library to determine the clearest path.

Act: Controls a DC motor drive system to pivot away from obstacles and resume forward motion.

### 🚀 Project Overview
This robot mimics basic biological navigation by constantly "scanning" its surroundings. Unlike standard single-sensor builds, this version uses three HC-SR04 sensors (Front, Left, and Right) to eliminate blind spots and provide a 180-degree field of awareness.

The system operates on a Sense-Think-Act logic loop:

Sense: Measures distances in three directions using ultrasonic pulses.

Think: Processes data via the NewPing library to determine the clearest path.

Act: Controls a DC motor drive system to pivot away from obstacles and resume forward motion.

### 🔧 Hardware Requirements
Microcontroller: Arduino Uno (or compatible)

Sensors: 3x HC-SR04 Ultrasonic Sensors

Motor Driver: L298N Dual H-Bridge

Chassis: 2WD or 4WD Robot Platform

Power: 7.4V - 12V DC Battery Source

Component,Pin (Arduino)
Front Sensor (Trig/Echo),10 / 9
Left Sensor (Trig/Echo),12 / 11
Right Sensor (Trig/Echo),8 / 7
Motor Left (IN1/IN2),6 / 5
Motor Right (IN3/IN4),4 / 3
