---

# 🚗 Car-Parking-System

> **A real-time distance detection system that mimics a car's reverse parking sensor using ultrasonic waves.**

---

## 📖 Overview

This project utilizes an **Arduino Uno** and an **HC-SR04 Ultrasonic Sensor** to detect the proximity of an object. As an object moves closer to the sensor, the system provides audio-visual feedback using an **LED** and a **Buzzer**.

It demonstrates fundamental concepts of **Embedded Systems**, including sensor interfacing, digital I/O control, and physics-based calculations in C++.

---

## ✨ Features

* **Real-time Distance Calculation:** Accurate measurement in centimeters using sonar.
* **Dual Alert System:** Visual (LED) and Audio (Buzzer) warnings.
* **Threshold Logic:** automatically triggers alarms when an object is within **10 cm**.
* **Serial Monitoring:** Live distance data output to the Serial Monitor for debugging.

---

## 🛠️ Hardware Required

| Component | Quantity | Description |
| --- | --- | --- |
| **Arduino Uno / Mega** | 1 | The brain of the project. |
| **HC-SR04 Sensor** | 1 | Ultrasonic distance sensor. |
| **Active Buzzer** | 1 | For the audio alarm. |
| **LED** | 1 | Any color (Red recommended). |
| **Resistor (220Ω)** | 1 | To protect the LED. |
| **Jumper Wires** | 6-8 | For connections. |
| **Breadboard** | 1 | For prototyping. |

---

## 🔌 Circuit Diagram & Wiring

### **Pin Connections**

| Component | Pin | Arduino Pin |
| --- | --- | --- |
| **HC-SR04** | VCC | 5V |
|  | GND | GND |
|  | TRIG | D9 |
|  | ECHO | D10 |
| **Buzzer** | (+) | D11 |
|  | (-) | GND |
| **LED** | Anode (+) | D13 |
|  | Cathode (-) | GND (via 220Ω Resistor) |

> **Note:** Ensure the LED polarity is correct (Long leg is +).



## 🚀 How to Run

1. **Clone the Repo:**
```bash
git clone https://github.com/MohdAnas-1436/Car-Parking-System.git

```


2. **Open in IDE:** Open `parking_sensor.ino` in the **Arduino IDE**.
3. **Connect:** Plug in your Arduino via USB.
4. **Upload:** Select your board and port, then hit **Upload**.
5. **Monitor:** Open **Serial Monitor** (9600 baud) to see the distance values!

---

## 🌐 Live Simulation (Wokwi)

Don't have hardware right now? You can run this project directly in your browser!

👉 **[Click here to view the Wokwi Simulation](h[ttps://www.google.com/search?q=%23](https://wokwi.com/projects/454865570889736193))**


*If you found this helpful, please star ⭐ this repository!*

```

### **Instructions for You:**
1.  **Create a file** named `README.md` in your GitHub repository.
2.  **Paste** the content above into it.
3.  **Replace placeholders:**
    * Change the `git clone` link to your actual repo link.
    * Paste your specific Wokwi project link where it says `(Paste your Wokwi link here!)`.
    * Update the LinkedIn/GitHub profile links at the bottom.

**Would you like me to create a "LICENSE" text file for you as well, to make the repository fully open-source compliant?**

```
