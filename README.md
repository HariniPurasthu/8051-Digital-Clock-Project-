⏰ 8051 Smart Digital Clock System

<p align="center">
  <b>🚀 Embedded System Project using AT89C51 Microcontroller</b><br>
  Real-Time Clock • Alarm • Stopwatch • LCD Interface
</p><p align="center">
  <img src="https://img.shields.io/badge/Microcontroller-AT89C51-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Language-Embedded%20C-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IDE-Keil%20uVision-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Simulation-Proteus-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>


📖 Overview

The 8051 Smart Digital Clock System is a fully functional embedded application built using the AT89C51 (8051) microcontroller.
It displays real-time time on a 16x2 LCD, supports alarm alerts, and includes a stopwatch mode for time tracking.

This project demonstrates core concepts of:

- ⏱ Timer Programming
- 🔌 Hardware Interfacing
- 🧠 Embedded System Design



🖼️ Project Showcase

<p align="center">
  <img src="images/overview1.png" width="650"/>


✨ Key Features

- 🕒 Real-time clock (HH:MM:SS)
- ⏰ Alarm with buzzer notification
- ⏱ Stopwatch for elapsed time
- 🔘 Multi-mode control via push buttons
- 📟 Clear LCD interface
- ⚙️ Accurate timer-based system



📸 Output Screens

<p align="center">
  <img src="images/normal%20clock%20reading.png" width="250"/>
  <img src="images/alarm%20set%201.png" width="250"/>
  <img src="images/stopwatch%20screen%201.png" width="250"/>
</p><p align="center">
  <img src="images/alarm%20buzzer.png" width="250"/>
  <img src="images/lcd%20close%20look.png" width="250"/>
  <img src="images/zoom%20of%20normal%20clock.png" width="250"/>


⚙️ How It Works

- The 8051 internal timer generates 1-second intervals
- Time is updated continuously and displayed on LCD
- Push buttons allow switching between modes
- Alarm triggers buzzer when time matches
- Stopwatch counts elapsed time independently



🔌 Hardware Components

- AT89C51 / 8051 Microcontroller
- 16x2 LCD Display
- Push Buttons
- Piezo Buzzer
- Crystal Oscillator
- Regulated Power Supply



💻 Software Tools

- Embedded C Programming
- Keil uVision IDE
- Proteus Simulation



🔄 Functional Modes

1. Clock Display Mode
2. Time Setting Mode
3. Alarm Setting Mode
4. Stopwatch Mode



▶️ Getting Started

🛠 Run Simulation

1. Open "simulation/digital_clock.pdsprj" in Proteus
2. Load ".hex" file from "build/"
3. Run simulation
4. Use buttons to control modes



📁 Project Structure

8051-Digital-Clock-Project/ │ ├── src/               # Embedded C source code ├── build/             # Compiled HEX file │   └── 8051_digital_clock.hex ├── simulation/        # Proteus project file │   └── digital_clock.pdsprj ├── images/            # Output images │   ├── overview1.png │   ├── normal clock reading.png │   ├── alarm set 1.png │   ├── stopwatch screen 1.png │   ├── alarm buzzer.png │   ├── lcd close look.png │   └── zoom of normal clock.png └── README.md



🧠 Skills Demonstrated

- Embedded C Programming
- 8051 Microcontroller Interfacing
- Timer & Counter Applications
- LCD Display Control
- Button Input Handling
- Circuit Simulation & Debugging



📌 Applications

- Digital Clock Systems
- Alarm Devices
- Embedded Learning Projects
- Timer-Based Applications



🚧 Future Enhancements

- RTC Module for higher accuracy
- Countdown Timer feature
- Temperature sensor integration
- Bluetooth-based control



👨‍💻 Author

Purasthu Harini



