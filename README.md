# -SMOKE-WATCH
SmokeWatch is a portable smoke and gas detection system using Arduino Uno and an MQ2 sensor. It monitors air quality in real time and triggers visual (LED) and audible (buzzer) alerts when hazardous levels are detected. Designed as a low-cost, safety-focused solution for indoor environments.
# SmokeWatch: Portable Smoke Detection and Alert System

SmokeWatch is a safety-oriented embedded systems project designed to detect smoke and hazardous gases in real time using an Arduino Uno and MQ2 gas sensor. The system provides both visual and audible alerts to ensure timely response in indoor environments.

## Project Objectives

- Develop a portable device for real-time smoke and gas detection.
- Implement visual and sound-based alert mechanisms.
- Calibrate sensor thresholds for reliable detection.
- Gain practical experience in embedded hardware development.

## Hardware Components

- Arduino Uno
- MQ2 Gas Sensor
- Red and Green LEDs
- Piezo Buzzer
- Breadboard and Jumper Wires
- Power Supply

## System Description

The MQ2 sensor continuously monitors air quality. When gas concentration exceeds a predefined threshold, the system activates a red LED and a piezo buzzer to indicate danger. Under safe conditions, a green LED remains lit. The system was tested by varying gas concentrations near the sensor and consistently produced accurate alerts.

## Repository Contents

- `code/smokewatch.ino`: Arduino source code for the device.
- `images/schematic.png`: Circuit schematic and hardware layout.
- `docs/project_report.pdf`: Detailed documentation of the project.
- `.gitignore`: Standard ignore file for Arduino projects.

## Skills Demonstrated

- Sensor interfacing and analog data acquisition
- Threshold calibration and real-time decision logic
- Embedded system design and testing
- Safety-focused hardware prototyping

