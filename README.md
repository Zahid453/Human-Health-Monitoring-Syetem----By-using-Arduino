# Human-Health-Monitoring-Syetem----By-using-Arduino
IoT-based Human Health Monitoring System ❤️ | Built with Arduino Uno and MAX30100 Pulse Oximeter Sensor to monitor heart rate and SpO₂ levels in real-time, displaying results on a 16x2 I²C LCD. Uses Arduino IDE and Python for data handling. This project was built during my third year of graduation (Semester V).

---

## 📌 Features
- Real-time measurement of **Heart Rate (BPM)** and **Oxygen Saturation (SpO₂)**.
- Portable and battery-powered design.
- Clear data display on a **16x2 I²C LCD**.
- Reliable readings with MAX30100 sensor.
- Simple to operate and cost-effective.

---

## 🛠️ Components Used
1. Exam Pad (for mounting components)
2. Arduino Uno + Connector wire
3. I²C-based 16x2 LCD display
4. Jumper Wires (Male-Male / Female-Female / Male-Female / Female-Male)
5. Black Wire Tape
6. MAX30100 Pulse Oximeter Sensor
7. Mini Breadboard
8. DC jack to HW battery connector
9. HW Battery

---

## 💻 Software & Programming
- **Arduino IDE** (for programming the Arduino Uno)
- **Python** (optional, for further data handling and visualization)

---

## 📦 Arduino Libraries Used
```cpp
#include <Wire.h>
#include "MAX30100_PulseOximeter.h"
#include <LiquidCrystal_I2C.h>

#define REPORTING_PERIOD_MS 1000

