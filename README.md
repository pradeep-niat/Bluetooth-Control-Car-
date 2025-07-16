# 📱 Bluetooth Controlled Arduino Car

This is an Arduino-based car project that uses Bluetooth (HC-05) to control the car wirelessly using an Android phone. It uses the L298N motor driver for controlling the motors and is great for beginners in robotics and embedded systems.

> ✅ Fun and interactive robotics project for beginners.

---

## 🚀 Features

- Control car using Bluetooth from mobile phone  
- Supports commands: Forward, Backward, Left, Right, Stop  
- Uses Android Bluetooth terminal app or custom app for control  
- Simple wiring with L298N motor driver and HC-05 Bluetooth module  
- Built on Arduino UNO platform  

---

## 🧰 Components Required

- Arduino UNO  
- HC-05 Bluetooth Module  
- L298N Motor Driver Module  
- 2x DC Motors with wheels  
- Chassis & Castor Wheel  
- 9V or 12V Battery  
- Jumper Wires  
- Android phone with Bluetooth app (e.g., Bluetooth Terminal)  
- Switch (optional)  

---

## 🔌 Circuit Connections

### HC-05 Bluetooth Module  
- VCC → 5V on Arduino  
- GND → GND on Arduino  
- TX → RX (Pin 0 on Arduino)  
- RX → TX (Pin 1 on Arduino) *Use voltage divider to step down 5V TX signal to 3.3V*  

### L298N Motor Driver  
- IN1 → Arduino Pin 8  
- IN2 → Arduino Pin 7  
- IN3 → Arduino Pin 6  
- IN4 → Arduino Pin 5  
- ENA → Arduino Pin 9  
- ENB → Arduino Pin 10  
- VCC → Battery Positive (+)  
- GND → Battery Negative (-) and Arduino GND  

### Motors  
- Left motor connected to L298N Output A  
- Right motor connected to L298N Output B  

---

## 📄 How It Works

1. The Arduino listens for Bluetooth commands sent from an Android phone app.  
2. Commands include 'F' (forward), 'B' (backward), 'L' (left), 'R' (right), and 'S' (stop).  
3. Depending on the command, the Arduino controls the motor driver to move the car accordingly.  

---

## 🧑‍💻 Author

**Pradeep Kumar S**  
📧 pradeepniatian@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/pradeep-kumar-s-61856336b)  

---

## 📃 License

This project is open for educational and personal use. Feel free to customize and learn!

---

