# 💡 Project: LED Control with Button & Temperature + Motion Detection with Alarm

---

## 🔷 Project 1: Turn LED On/Off Using a Push Button
<img width="1918" height="808" alt="لقطة شاشة 2025-07-17 170824" src="https://github.com/user-attachments/assets/fcf611a1-346e-4c3e-9df9-853871cda761" />


This project demonstrates how to control an LED using a single push button. Pressing the button once turns the LED on, and pressing it again turns it off.

### 🧰 Components Used:
- Arduino Uno board  
- Push button  
- 10kΩ resistor (for pull-down configuration)  
- 220Ω resistor (for LED protection)  
- LED  
- Breadboard  
- Jumper wires

### ⚙️ How It Works:
The Arduino reads the state of the push button. When the button is pressed, it toggles the LED state between ON and OFF. A variable is used to remember the current state of the LED.

---

## 🔷 Project 2: Temperature Display with Motion Detection Alarm


<img width="728" height="460" alt="لقطة شاشة 2025-07-17 174554" src="https://github.com/user-attachments/assets/73ef2718-3e7c-474a-b511-07a83297b2ac" />

This project uses a TMP36 sensor to measure temperature and displays the result on an LCD screen. If motion is detected using an IR or PIR sensor, a buzzer is triggered as an alert.

### 🧰 Components Used:
- Arduino Uno board  
- TMP36 temperature sensor  
- IR or PIR motion sensor  
- 16x2 LCD display  
- Buzzer  
- 10kΩ resistor (optional for sensor stability)  
- Breadboard  
- Jumper wires

### ⚙️ How It Works:
- The TMP36 sensor outputs an analog voltage that corresponds to the temperature. The Arduino reads this and converts it to Celsius.
- The temperature is continuously displayed on the LCD.
- When motion is detected by the IR or PIR sensor, the buzzer is activated to produce a sound alert.
