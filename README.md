# 🔀 Dip Switch – Arduino LED Control

**Dip Switch** is a simple Arduino project that demonstrates digital input and output using a 3-way DIP switch and 3 LEDs. When a switch is flipped **ON**, the corresponding **LED lights up**. This is a great beginner project to learn about digital pins, switches, and controlling outputs with inputs.

---

## 📝 Description

This project uses a DIP switch with 3 individual switches. Each switch is connected to one LED through a digital input/output pin. When a switch is flipped, it sends a **HIGH** signal to the Arduino, which turns on the corresponding LED. It’s a clean, hands-on way to understand digital control with basic components.

---

## 🔧 Components Used

- 1 × Arduino Uno (or compatible board)  
- 1 × Breadboard  
- 1 × 3-way DIP Switch  
- 3 × LEDs (any color)  
- 6 × Resistors (220Ω for LEDs, 10kΩ for DIP pull-down)  
- 11 × Jumper Wires  

---

## 🛠️ Installation & Setup

### 1. Wiring

- Connect each DIP switch pin to a digital input pin on the Arduino (e.g., pins 2, 3, 4).
- Add **10kΩ pull-down resistors** on each DIP switch line to GND to ensure stable LOW readings.
- Connect the other side of each DIP switch to **5V**.
- Connect 3 LEDs to digital output pins (e.g., pins 8, 9, 10) with **220Ω current-limiting resistors** in series to GND.

## ⚙️ How It Works
Each DIP switch is connected between 5V and an Arduino digital input pin, with a pull-down resistor to GND.

When a switch is flipped ON, it connects 5V to the input pin, making it HIGH.

The Arduino reads the state of each input and sets the corresponding LED pin HIGH or LOW accordingly.

The LED turns ON or OFF based on the input state.

## 📸 Images / 🎥 Videos




🎞️ videos/dip-switch-demo.mp4(https://drive.google.com/file/d/1QaSX4vQ3d6KTMMfO7oBr-oPxJBPpJSZF/view)

## 🔗 Simulation Links


Tinkercad Circuit(https://www.tinkercad.com/things/1kAq7TcGdp4-copy-of-dip-switch/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard%2Fdesigns%2Fcircuits)

## 🙌 Credits
Project by: Jaden Chapman

Made with ❤️ using Arduino

Inspired by basic digital I/O principles
