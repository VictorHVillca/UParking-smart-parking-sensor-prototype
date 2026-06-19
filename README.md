# Smart Parking Sensor Prototype 🚗🔋

An intelligent IoT parking sensor system developed during the Mechatronics Engineering program at UPSA. This project won **2nd Place** in the annual faculty science fair.

## 📋 Overview
This project solves a common urban and campus problem: the loss of time and fuel searching for parking spaces during peak hours. The system detects the presence of a vehicle in a specific parking slot in real-time and transmits this availability status to a centralized web application.

### Key Features:
- **Edge Detection:** Real-time car detection using ultrasonic/infrared sensors integrated with an ESP32 microcontroller.
- **IoT Connectivity:** Data transmission via Wi-Fi to a web server utilizing HTTP request protocols.
- **Data Analytics:** Centralized database storage allowing historical data parsing and bar chart visualization of peak occupancy hours.

---

## ⚙️ System Architecture
Since the core firmware is currently embedded inside the production microcontroller, the system logic is structured as follows:
1. **Hardware Layer:** ESP32 Microcontroller + Presence Sensor + Power Management.
2. **Network Layer:** Local Wi-Fi connection utilizing HTTP request protocols to upload occupancy states.
3. **Software & Cloud Layer:** Web server capturing states, saving logs into a database, and displaying statistical charts.

---

## 📐 Mechanical Design & Manufacturing (CAD)
The protective enclosure for the electronics was fully designed from scratch using **Autodesk Fusion 360** and manufactured via 3D printing. The design features a two-piece interlocking system to ensure easy assembly, component protection, and quick mounting features.

### Enclosure Breakdown & Views:

1. **Full Assembly View (Opposite Angle):** This view shows both pieces oriented to display the external faces and features that are not visible when looking at the components individually.
   ![Full Assembly Layout](https://github.com/VictorHVillca/UParking-smart-parking-sensor-prototype/raw/7d4af2492d3faf84ad27966e36d2d9605dd26dc0/TecnoUPSA%202026%20Render1.png)

2. **Base Enclosure (Internal Rails View):** This render shows the second component flipped upside down to highlight the custom interlocking rail system designed for a precise mechanical fit with the main shell.
   ![Base with Guide Rails](https://github.com/VictorHVillca/UParking-smart-parking-sensor-prototype/raw/7d4af2492d3faf84ad27966e36d2d9605dd26dc0/TecnoUPSA%202026%20Render2.png)

3. **Main Shell Component:** The primary enclosure piece designed to house the ESP32 microcontroller and sensor alignment.
   ![Main Shell Component](https://github.com/VictorHVillca/UParking-smart-parking-sensor-prototype/raw/7d4af2492d3faf84ad27966e36d2d9605dd26dc0/TecnoUPSA%202026%20Render3.png)

---

## ⚡ Hardware & Electronics
My main contribution to this project centered around the **hardware assembly, circuit routing, and 3D enclosure design**.

### Component List:
- **Microcontroller:** ESP32 (NodeMCU).
- **Sensor:** Vehicle Detection Sensor (Ultrasonic setup).
- **Enclosure:** Custom 3D Printed PLA/ABS shell.

*Note: The schematic diagram is currently undergoing optimization and layout routing updates in an industry-standard EDA software to match professional manufacturing guidelines. Updates will be uploaded soon.*

---

## 🏆 Awards & Recognition
- **2nd Place** at **TecnoUPSA 2026** (Annual Faculty Science & Technology Fair).
  - **Category:** Electronics and Mechatronics (Category 1).
  - **Course:** Fundamentals of IT (*Fundamentos de TI*).
  - **Final Evaluation Score:** 90.67 / 100 points.
