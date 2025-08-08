# Mini Radar with Arduino

[Miniradar](https://www.youtube.com/watch?v=GVkE3fTdrYw&t=1s).

## 📋 Overview
This project will guide you through building a **mini radar system** using **Arduino**, an **ultrasonic sensor**, and a **servo motor**.  
The radar will scan its surroundings and detect nearby objects, displaying the distance and angle in real time.

---

## 🛠️ Components Required
- **Arduino Uno** (or compatible board)
- **HC-SR04 Ultrasonic Sensor**
- **SG90 Servo Motor**
- Breadboard & Jumper Wires
- USB Cable for programming
- (Optional) OLED/LCD display or a PC with Processing for visualization

---

## 🔌 Wiring Diagram

### **Ultrasonic Sensor (HC-SR04)**
| HC-SR04 Pin | Arduino Pin |
|-------------|-------------|
| VCC         | 5V          |
| GND         | GND         |
| Trig        | D9          |
| Echo        | D10         |

### **Servo Motor (SG90)**
| Servo Wire       | Arduino Pin |
|------------------|-------------|
| Red (VCC)        | 5V          |
| Brown/Black (GND)| GND         |
| Orange/Yellow (Signal)| D11    |

---

💻 Arduino Code : /adr_radar.ion

## 📊 Optional: Radar Visualization

If you want to display the radar sweep on your PC screen, use **Processing** software.

1. Download and install [Processing](https://processing.org/download).
2. Connect Arduino to your computer.
3. Upload the Arduino code above.
4. Run the Processing radar visualization sketch (ask if you need the sample code).

---

## 🚀 Steps to Build

1. **Prepare Components** — Gather Arduino, HC-SR04, servo motor, and jumper wires.
2. **Wire the Circuit** — Follow the wiring diagram above.
3. **Upload Arduino Code** — Use Arduino IDE to flash the provided code.
4. **Test the Radar** — Open Serial Monitor to see distance readings.
5. **(Optional)** Set up Processing visualization for a sci-fi-style radar display.

💻 Processing Code : /sketch_250808a/sketch_250808a.pde
