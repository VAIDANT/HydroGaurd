# 🌿 HydroGuard

**HydroGuard** is our first working version of an **automated irrigation system** built using **Arduino Uno**, a **soil moisture sensor**, and a **relay-controlled pump**.  
It automatically waters plants by detecting soil dryness, helping conserve water and reduce manual effort through simple, efficient automation.

---

## ⚙️ Features
- Detects soil moisture using an analog sensor.  
- Automatically turns the pump **ON/OFF** based on dryness level.  
- Displays soil condition and pump status on a **16x2 LCD**.  
- Simple, reliable, and completely hardware-based — no app or Wi-Fi required.

---

## 🧠 Components Used
- Arduino Uno  
- Soil Moisture Sensor (Analog)  
- Relay Module  
- 16x2 LCD Display (without I2C)  
- Jumper wires and power supply

---

## 🔌 Working Principle
1. The soil moisture sensor sends an analog reading (0–1023) to the Arduino.  
2. If the reading is **below 400**, the soil is dry — the **relay activates the pump**.  
3. When the soil becomes moist again, the **pump turns off automatically**.  
4. The LCDs show both the soil status and pump activity in real time.

---

## 💻 Code
The complete Arduino code is included in this repository under `HydroGuard.ino`.  
It uses the `LiquidCrystal` library to drive the LCD and basic conditional logic to control the relay and pump.

---

## 💡 Background
This project originated as a collaborative school initiative designed to combine creativity and practical problem-solving through technology.  
It taught us how sensors, programming logic, and hardware integration can work together to make daily life simpler and more sustainable.  

We plan to expand HydroGuard in the future by adding:
- Ultrasonic water-level monitoring  
- Rain detection  
- Bluetooth app connectivity  

---

## 👥 Team
- **Vaidant Jindal** – Circuit design, coding, and documentation  
- **Vrinda Katoch** – Assembly, testing, and project coordination  

### 🧑‍🏫 Supervisor
- **Ms. Karuna Bhambh** – Project guidance and mentorship  

---

## 👨‍💻 Authors
**Vaidant Jindal**  
- [GitHub Profile](https://github.com/VAIDANT)  
- Student at Kundan Vidya Mandir, Ludhiana  
- Passionate about technology, innovation, and sustainability 🌍

**Vrinda Katoch**  
-Former Student at Kundan Vidya Mandir, Ludhiana  
