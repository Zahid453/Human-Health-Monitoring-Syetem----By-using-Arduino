# Human-Health-Monitoring-System----By-using-Arduino
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
2. Arduino Uno + Connector Wire
3. I²C-based 16x2 LCD Display
4. Jumper Wires (Male-Male / Female-Female / Male-Female / Female-Male)
5. Black Wire Tape
6. MAX30100 Pulse Oximeter Sensor
7. Mini Breadboard
8. DC Jack to HW Battery Connector
9. HW Battery

---

## 💻 Software & Programming
- **Arduino IDE** (for programming the Arduino Uno)
- **Python** (optional, for further data handling and visualization)

---

## 📸 Output Results

<table>
  <tr>
    <td><img src="Result%20--%20Photos%20%26%20Vedios/Main%20Circuit.jpg" width="300"/></td>
    <td><img src="Result%20--%20Photos%20%26%20Vedios/Result%20--%20I.jpg" width="300"/></td>
    <td><img src="Result%20--%20Photos%20%26%20Vedios/Result%20--%20II.jpg" width="300"/></td>
  </tr>
</table>

---

## 🎥 Working Video
[▶ Watch Working Video](Result%20--%20Photos%20%26%20Vedios/Working.mp4)

---

## 👤 Author
**Zahid Shaikh**  
- LinkedIn: [https://www.linkedin.com/in/skzahid90281/](https://www.linkedin.com/in/skzahid90281/)

---

## 📦 Arduino Libraries Used
```cpp
#include <Wire.h>
#include "MAX30100_PulseOximeter.h"
#include <LiquidCrystal_I2C.h>

#define REPORTING_PERIOD_MS 1000
