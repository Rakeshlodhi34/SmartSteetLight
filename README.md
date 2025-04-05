# Smart Street Light System

## Overview

This project is a part of our Bachelor's degree in Electronics and Communication Engineering at VIT Bhopal. The goal is to design and build an energy-efficient **Smart Street Light System** that uses sensors and microcontrollers to automatically manage street lighting based on ambient conditions and human activity.

## Features

- Automatic street light ON/OFF based on light intensity (LDR sensor)
- Motion detection using IR sensors to reduce energy waste
- Energy-saving mode during low activity hours

## Technologies Used

- **Microcontroller**: Arduino UNO / NodeMCU (depending on version)
- **Sensors**: LDR (Light), IR (Motion)
- **Actuators**: LED street lights 
- **Power Supply**: 12V DC adapter
- **Programming**: C++ (Arduino IDE)

## Hardware Requirements

- Arduino UNO / NodeMCU
- LDR Sensor
- IR  Sensors
- LEDs 
- Resistors, Breadboard, Jumper Wires
- Power Supply

## Software Requirements

- Arduino IDE
- Serial Monitor for debugging

## How It Works

1. The system uses an LDR to measure ambient light.
2. If it's dark, the PIR sensor checks for human motion.
3. If motion is detected, the lights turn ON.
4. If no motion is detected, the lights stay OFF or run in dim mode (optional).
5. During the daytime, lights remain OFF regardless of motion.
