
# 🐭 Micromouse Robot – Custom PCB Design

This repository contains the **custom PCB design** for a Micromouse autonomous maze-solving robot. The design was inspired by the **Green Giant Micromouse**, a popular open-source project, and has been tailored to support modular, scalable, and competition-ready robotic development.

---

## 📦 Project Summary

Micromouse robots are small autonomous vehicles designed to solve mazes as quickly as possible. This PCB is the main controller board for such a robot, integrating motor drivers, sensors, power management, and microcontroller components in a compact footprint.

This design builds upon the **Green Giant Micromouse** architecture, with improvements for component sourcing, layout optimization, and modularity for further development.

---

## 🧠 Features & Specifications

| Category               | Description                                               |
|------------------------|-----------------------------------------------------------|
| **Microcontroller**    | STM32F4 / STM32F1 series (footprint supports both)        |
| **Motor Drivers**      | DRV8833 Dual H-Bridge for 2 DC motors                     |
| **Sensors**            | IR distance sensors (front, left, right, 45 digree) – 5 sensors |
| **Power System**       | 2-cell Li-ion with step-down regulator (5V and 3.3V rails)|
| **Connectivity**       | Serial debug headers, encoder inputs, IR TX/RX support    |
| **Form Factor**        | Compact 2-layer PCB, optimized for wheel/motor layout     |
| **Reference Design**   | Based on Green Giant Micromouse with custom adaptations   |

---

## 📐 PCB Design Overview

- Designed using **Eagle**
- Two-layer layout with clear separation of power and logic
- Silkscreen indicators for debugging and easy assembly
- Power and signal decoupling capacitors for noise stability
- Modular connector options for plugging in sensors and actuators

---


## 🧪 Testing & Next Steps

- Motor driver tested with small DC gear motors (30:1)
- Voltage rails tested with onboard regulators (5V and 3.3V)
- IR sensors and encoders interfaced with STM32 test code
- Future integration: PID motor control, maze-solving algorithm, IMU

---

## 📝 Acknowledgment

This design is heavily inspired by the [Green Giant Micromouse](https://github.com/davidtavarez/green-giant) project and adapted for educational and competitive use.

---

## 👨‍💻 Author

**Thamara Banneheka**  
Embedded Systems & Robotics Enthusiast  
📧 thamaradasantha@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/thamara-dasantha-banneheka/)
