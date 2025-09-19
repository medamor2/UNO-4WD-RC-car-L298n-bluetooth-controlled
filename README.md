UNO-4WD-RC-car-L298n-bluetooth-controlled
# 🚙 Arduino 4WD RC Car (UNO + L298N + Bluetooth)

This project is a **DIY 4-wheel drive robotic car** powered by an Arduino UNO, an L298N motor driver, and an HC-05 Bluetooth module.  
It can be controlled from any Android phone using a Bluetooth remote app.

---

## ✨ Features
- 🚗 Forward, backward, left, and right movement  
- ⚡ Motor speed control via PWM (optional)  
- 📱 Control with Android Bluetooth app  
- 🔋 Runs on battery pack  

---

## 🛠️ Hardware Requirements
- Arduino UNO  
- L298N Motor Driver Module  
- HC-05 / HC-06 Bluetooth module  
- 4 DC Motors + 4WD chassis  
- Battery

---

## 💻 Software Requirements
- [Arduino IDE](https://www.arduino.cc/en/software)  
- Bluetooth RC Controller app (available on Google Play Store)  

---

## 🔌 Wiring Diagram
| Arduino Pin | L298N Input | Function       |
|-------------|-------------|----------------|
| D5          | IN1         | Motor A        |
| D6          | IN2         | Motor A        |
| D9          | IN3         | Motor B        |
| D10         | IN4         | Motor B        |
| D7          | ENA         | Enable Motor A |
| D8          | ENB         | Enable Motor B |

