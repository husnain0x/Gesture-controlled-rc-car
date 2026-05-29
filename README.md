# 🚗 Gesture-Controlled RC Car

> Control a car with hand gestures — no buttons, no joystick.

Control a car with hand gestures using MPU6050 and NRF24L01

## 📌 Overview
This project uses hand tilt angles detected by the MPU6050
to wirelessly drive a car via NRF24L01 modules and two
Arduino Nanos — one as transmitter (glove side),
one as receiver (car side).

---

## 🧰 Components Used

| Component | Purpose |
|---|---|
| Arduino Nano x2 | Transmitter & Receiver |
| MPU6050 | Detects hand tilt (X/Y axis) |
| NRF24L01 | 2.4GHz wireless communication |
| L298N Motor Driver | Controls car motors |
| RC Car Chassis | The vehicle |

---

## ⚙️ How It Works
