# 🔔 IR Proximity Sensor – Touchless Doorbell Module

A simple and effective DIY project to design a **touchless doorbell** using an IR proximity sensor. This circuit uses the LM358 operational amplifier to detect hand gestures or presence near the sensor, triggering a buzzer without the need to physically press a button — perfect for hygienic interaction in a post-pandemic world.

---

## 🌟 Overview

The project was inspired by the need for contactless solutions during the COVID-19 pandemic. Traditional doorbells can act as a surface for virus transmission. This module solves that issue using infrared (IR) sensing technology to detect presence or motion and activate a buzzer — no touch required!

---

## 🎯 Objectives

- Understand the working of a touchless IR-based doorbell
- Learn the circuit design and use of LM358 as a comparator
- Explore basic analog electronics and sensor interfacing

---

## 🧰 Components Required

| Component                   | Quantity |
|----------------------------|----------|
| LM358 IC                   | 1        |
| Zero PCB Board             | 1        |
| IR Transmitter & Receiver  | 1 pair   |
| Buzzer                     | 1        |
| LED                        | 1        |
| 10KΩ Variable Resistor     | 1        |
| Fixed Resistors (100Ω, 220Ω, 10KΩ) | As needed |
| Connecting Wires           | Several  |

---

## 📐 Circuit Explanation

The circuit uses:
- **IR LED and Photodiode Pair** to detect reflected IR light from an object (like a hand).
- **LM358 IC** configured as a comparator:
  - **Pin 2 (Non-Inverting Terminal)** connected to a variable resistor to set threshold
  - **Pin 3 (Inverting Terminal)** connected to IR sensor output
  - **Pin 1 (Output)** goes HIGH when IR is detected, triggering the **buzzer** and **LED**

This simple setup allows users to wave their hand to ring the bell without physical contact.

---

## 🔧 How It Works

1. When no object is in front of the sensor, IR light is not reflected — output stays LOW.
2. When a hand approaches, IR light reflects onto the photodiode.
3. Voltage across the photodiode increases, triggering LM358’s output HIGH.
4. This HIGH signal activates the buzzer and LED, acting as a "touchless bell".

---
## 📊 Diagrams

### 🔌 Circuit Diagram  

- [Circuit Diagram](https://github.com/DuttPanchal04/IR-Proximity-Sensor-Touch-less-Doorbell-Module/blob/main/IR%20Sensor%20Circuit.pdf)

*(Add your circuit diagram here as an image)*

### 🔬 Breadboard View  

- [Breadboard View](https://github.com/DuttPanchal04/IR-Proximity-Sensor-Touch-less-Doorbell-Module/blob/main/IR%20Proximity%20Sensor%20Touch%20Less%20Doorbell%20Breadboard%20View.png)

*(Add your breadboard image here)*

## 📦 Applications

- 🚪 Touchless Doorbells
- 🧼 Automatic Hand Dryers
- 🚷 Motion-Activated Doors

## 📘 Documentation

[Full Project Report PDF](https://github.com/DuttPanchal04/IR-Proximity-Sensor-Touch-less-Doorbell-Module/blob/main/IR%20Proximity%20Sensor_Touchless%20Doorbell%20Module.pdf)

## 🧠 Learnings

- Basics of IR proximity sensors
- Role of operational amplifiers in analog signal comparison
- Designing a contactless human interface system

## 🤝 Connect

Project by Dutt Panchal.
- 📧 Email: dattpanchal2904@gmail.com
- 🔗 [GitHub](https://github.com/DuttPanchal04)
- 🔗 [LinkedIn](https://www.linkedin.com/in/dattpanchal04/)

⭐ If you found this project helpful, consider giving it a star!