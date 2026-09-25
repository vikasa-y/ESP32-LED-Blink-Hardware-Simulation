# 💡ESP32 LED Blink Hardware Simulation

This is my **first beginner-level embedded/hardware project**, created while I am learning the fundamentals of electronics, embedded systems, and IoT.

The project is a simple ESP32 LED blinking circuit developed using **PlatformIO** and tested using the **Wokwi hardware simulator**.

I intentionally started with a simple project to understand the basic workflow of an embedded project before moving toward sensors, communication protocols, IoT systems, and more advanced embedded applications.

## 📄 About the Project

The ESP32 controls an LED connected through a resistor. The LED repeatedly turns ON and OFF with a short delay.

Although the project itself is simple, it helped me practice the basic concepts involved in starting an embedded project:

- ESP32 basics
- GPIO output
- LED control
- Basic LED and resistor connections
- PlatformIO project structure
- Arduino framework
- Hardware simulation using Wokwi
- Running and testing embedded code
- Basic Git and GitHub workflow

## 🛠️ Hardware

- ESP32 DevKit
- LED
- 1kΩ Resistor

## 🧑‍💻 Software & Tools

- PlatformIO
- Arduino Framework
- VS Code
- Wokwi Simulator
- Git & GitHub

## Circuit & Simulation

The ESP32 GPIO pin is connected to the LED through a 1kΩ resistor, with the LED connected to GND.

The project was developed and tested using the **Wokwi hardware simulator**.

```

This project is a **simulation-based project** and does not represent a physical hardware build.

```
## ⚙️ How It Works

The ESP32 runs a simple program that continuously:

1. Turns the LED ON.
2. Waits for a short delay(1 sec).
3. Turns the LED OFF.
4. Waits again.
5. Repeats the process.

This creates the basic LED blinking behavior.

## 📂 Project Structure

```text
ESP32-LED-Blink-Hardware-Simulation/
├── src/
│   └── main.cpp
├── test/
│   ├── diagram.json
│   └── wokwi.toml
├── images/
│   └── wokwi-simulation.png
├── include/
├── lib/
├── platformio.ini
├── .gitignore
└── README.md
```
## 🎯 What I Learned
This project gave me practical experience with the basic embedded development workflow:
```
Write Code
    ↓
PlatformIO
    ↓
Build Firmware
    ↓
Run ESP32 Simulation
    ↓
Observe & Test
    ↓
Improve
```
It also helped me understand how software code interacts with a simple hardware circuit and how an ESP32 can control an external component through a GPIO pin.

## 🎯 Learning Focus

This project focuses on building my foundation in embedded systems by practicing:

- ESP32 fundamentals
- GPIO and digital output
- Basic LED and resistor circuits
- Understanding simple hardware connections
- Arduino-based embedded programming
- PlatformIO project workflow
- Wokwi hardware simulation
- Basic testing and debugging
- Git and GitHub project workflow

The goal is to understand the fundamentals first and gradually move toward more complex embedded and IoT projects.