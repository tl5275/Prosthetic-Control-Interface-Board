# Prosthetic Control Interface Board

A compact embedded hardware platform designed for prosthetic control applications using the ESP32-WROOM-32 microcontroller. The PCB integrates sensor interfacing, actuator control, communication interfaces, and USB programming support into a single modular design.

---

# Project Overview

This project implements a custom 2-layer PCB for interfacing:
- EMG sensors
- Flex sensors
- External actuators / motors

The ESP32 processes biological and motion-related input signals and controls output devices through MOSFET-based driver circuits.

The board also includes:
- USB Type-C programming interface
- CH340C USB-UART converter
- UART and I2C communication headers
- 3.3V regulated power supply
- Ground plane implementation
- Differential USB routing

---

# Features

- ESP32-WROOM-32 based embedded processing
- EMG and flex sensor interfacing
- MOSFET actuator driver section
- USB Type-C programming support
- UART and I2C headers
- Reverse polarity protection
- Ground polygon pour for noise reduction
- Compact 2-layer PCB layout
- Manufacturable prototype design

---

# Hardware Specifications

| Parameter | Value |
|---|---|
| PCB Layers | 2 |
| PCB Material | FR4 |
| Copper Thickness | 1 oz |
| Microcontroller | ESP32-WROOM-32 |
| USB Interface | USB Type-C |
| USB-UART IC | CH340C |
| Voltage Regulator | LD1117-3.3V |
| Motor Driver | MOSFET Based |
| Communication | UART, I2C |
| Design Software | EasyEDA |

---

# System Architecture

The PCB architecture is centered around the ESP32-WROOM-32 microcontroller. Sensor signals from EMG and flex sensors are processed by the ESP32 and used to drive external actuators through MOSFET switching stages.

The board also includes:
- regulated 3.3V power generation
- USB programming interface
- communication headers
- noise-aware PCB routing strategy

---
