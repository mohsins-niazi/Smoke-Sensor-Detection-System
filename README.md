# 📑 Smoke Sensor & Detection System | Simulation + Hardware

This repository contains the complete documentation, circuit simulation, and hardware implementation details for the Smoke Sensor project developed during my 3rd Semester for the **Electronic Devices and Circuits (EDC)** course.

## 🛠️ Project Overview
The system is designed using the **MQ-2 smoke sensor** to detect smoke and combustible gases in the environment. It provides a visual notification (LED indication) automatically when gas concentrations exceed the safe threshold.


## ⚙️ Working Principle
1. **Sensing:** The MQ-2 sensor continuously monitors the smoke concentration in the air.
2. **Amplification/Switching:** When smoke is detected, the sensor output voltage increases, switching the transistor to an **ON** state.
3. **Indication:** The active transistor allows current to flow through the circuit, turning the **LED ON** to alert users.


## 🔬 Project Demonstration (3 Stages)

### 🔷 Stage 1: Simulation (No Smoke Condition)
* In this state, no smoke or hazardous gas is present.
* The sensor output remains LOW, the transistor stays OFF, and the LED is completely dark, indicating a clean and safe environment.

### 🔷 Stage 2: Simulation (Smoke Detected)
* When smoke simulation is activated, the MQ-2 sensor output voltage jumps.
* This base voltage turns the transistor ON, completing the circuit path and causing the LED to glow, confirming threat detection.

### 🔷 Stage 3: Hardware Implementation
* The verified circuit logic is deployed onto a physical breadboard using real electronic components.
* Introducing real smoke near the physical MQ-2 sensor triggers the hardware circuit, lighting up the physical LED and validating the system's real-world working.


## 📦 Components Used
* MQ-2 Gas/Smoke Sensor
* BJT Transistor (Switching)
* LED (Visual Indicator)
* Resistors & Connecting Wires
* Breadboard & Power Source


## 🧠 Learning Outcomes
* **Simulation vs. Hardware:** Understood how theoretical models behave in virtual environments versus real-world physical constraints.
* **Sensors Application:** Gained hands-on experience with the practical working, calibration, and interfacing of the MQ-2 smoke sensor.
* **BJT as a Switch:** Mastered the concept of using a Transistor (BJT) as an automatic electronic switch based on sensor threshold voltages.
* **Prototyping:** Developed skills in hardware circuit design and clean implementation on a breadboard.

## 🎯 Conclusion
This project successfully bridge the gap between academic theory and practical implementation, strengthening my core understanding of electronic components, safety automation systems, and hardware prototyping.

