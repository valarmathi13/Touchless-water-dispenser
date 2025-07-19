# Touchless-water-dispenser
# Touchless Water Dispenser using IR Sensor and Arduino (Simulated)

This project demonstrates a **touchless water dispenser** system using an **IR proximity sensor** and an **Arduino Uno**. When a hand is detected near the sensor, an output device (LED/motor) is activated to simulate the dispensing of water. This is a **simulation-only project** built and tested on **Tinkercad**.

---

## 🔧 Tools & Technologies
- Arduino Uno
- IR Proximity Sensor
- LED (used to simulate solenoid/motor)
- Tinkercad Circuits (for simulation)
- Arduino IDE

---

## 🛠️ Components Used
- 1 × Arduino Uno
- 1 × IR Sensor Module
- 1 × LED or DC Motor (for output simulation)
- 1 × 220Ω Resistor (for LED)
- Jumper Wires & Breadboard

---

## ⚙️ Working Principle
1. The IR sensor detects the presence of a hand within ~5–10 cm.
2. The Arduino reads the IR sensor's digital output.
3. If a hand is detected, Arduino activates an LED (or motor) for a few seconds to simulate water flow.
4. Once the hand is removed or the timer ends, the output is turned OFF.

---

## 🧪 Simulation in Tinkercad
If no real hardware is used, this project can be fully simulated in Tinkercad.

🔗 **Tinkercad Simulation Link**: [Add your Tinkercad share link here]

---

## 💬 Serial Monitor Output
```text
Hand Detected!
Water Dispensing...
Done!
