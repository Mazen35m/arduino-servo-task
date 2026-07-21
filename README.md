# Arduino Multi-Servo Synchronization & Sweep Task

## 📋 Project Overview
This project is an Arduino-based automation task designed to control **4 Micro Servo Motors** simultaneously. The system executes a specific sequence divided into two main phases:
1. **Sweep Phase:** All four servos perform a synchronized sweeping motion (back and forth from 0° to 180°) for a precise duration of **2 seconds** using a non-blocking millis-based timer.
2. **Hold Phase:** Immediately after the 2-second window expires, all servo motors automatically lock and hold their positions steadily at **90 degrees**.

---

## 🛠️ Components & Hardware Requirements
* **Arduino Uno** (or compatible board)
* **4x Micro Servo Motors**
* **Breadboard & Jumper Wires**
* External Power Supply / USB Connection (ensure proper current distribution for the servos).

---

## 🔌 Circuit Wiring Diagram

Connect the components as follows:

| Component / Pin | Arduino Pin | Description |
| :--- | :--- | :--- |
| **Servo 1 Signal** | Pin 10 | PWM control for Motor 1 |
| **Servo 2 Signal** | Pin 11 | PWM control for Motor 2 |
| **Servo 3 Signal** | Pin 12 | PWM control for Motor 3 |
| **Servo 4 Signal** | Pin 13 | PWM control for Motor 4 |
| **VCC (All Servos)** | 5V | Power supply rail |
| **GND (All Servos)** | GND | Common ground connection |




