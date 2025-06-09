# LnT-Project
# 🚗 Alcohol Detection System for Vehicles

A microcontroller-based prototype that detects alcohol consumption in drivers using a gas sensor and stops the vehicle in response. This project simulates the functionality using Arduino Uno, LEDs, buzzer, LCD display, and a DC motor.

---

## 🧠 Problem Statement

To design a system capable of detecting alcohol levels in a driver and stopping the vehicle if intoxication is detected — aiming to reduce drink-and-drive accidents.

---

## 🎯 Project Objectives

1. **System Integration**: Combine gas sensor, LEDs, LCD, buzzer, and DC motor using Arduino Uno R3.
2. **Alcohol Detection Logic**: Identify intoxication based on gas sensor threshold.
3. **User Feedback**:
   - "SAFE" message and green LED if no alcohol is detected.
   - "ALCOHOL DETECTED" message, red LED, buzzer alert, and vehicle stop if threshold is exceeded.
4. **Simulation**: Circuit tested on **TinkerCAD** and deployed via **Arduino IDE**.

---

## 🔧 Hardware Used

- Arduino Uno R3
- MQ-3 Gas Sensor
- Piezo Buzzer
- LCD 16x2
- Red and Green LEDs
- DC Motor
- Resistors, jumper wires, breadboard

---

## 💻 Software Tools

- https://www.tinkercad.com/
- https://www.arduino.cc/en/software

---
## 📂 Repository Structure

```
LnT-Project/
├── VIT_Vellore_21BEC0299/
│   └── Alcohol_Detection.ino      # Arduino code for system logic
├── Project Report.pdf             # Full project documentation
├── Simulation Video.mp4           # Video demonstration
├── test/                          # (Optional testing folder placeholder)
└── README.md                      # You're here!
```
---

## 🛠️ How It Works

1. **Sensor Reading**:
   - Reads analog value from MQ-3 sensor.
2. **Threshold Logic**:
   - `sensorThresh = 400` (modifiable).
   - If value > 400 → trigger alert.
3. **Actions on Detection**:
   - Red LED ON, buzzer sounds, LCD displays messages.
   - Simulated car (DC motor) is stopped.
4. **Actions on Safety**:
   - Green LED ON, car keeps running.

---

## 🔁 Sample LCD Output

SAFE

-- or --

ALCOHOL DETECTED
SENDING ALERT
STOPPING CAR...

---

## 🚀 Getting Started

### 1. Upload to Arduino
- Open `Alcohol_Detection.ino` in Arduino IDE.
- Select correct board (Arduino Uno) and port.
- Click `Upload`.

### 2. Simulate in TinkerCAD *(Optional)*
- Open the circuit diagram in TinkerCAD.
- Upload code and simulate sensor readings.

---

## 📽️ Demo

📺 Watch the full simulation: `Simulation Video.mp4` (in repo)

---

## 👨‍🔧 Author

Developed by **Venkata Sai Sathvik Rajampalli**  
VIT Vellore | ID: 21BEC0299

---

## 📃 License

This project is licensed under the MIT License.
