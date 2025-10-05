# 🧅 Kand Sanrakshan — Smart Onion Storage System

[Live Site](https://kandsanrakshan.netlify.app/)

---

## ⚙️ Table of Contents

1. [Overview](#overview)
2. [Problem Statement](#problem-statement)
3. [Solution & Features](#solution--features)
4. [Technology Stack](#technology-stack)
5. [How It Works](#how-it-works)
6. [Project Progress](#project-progress)
7. [Impact & Benefits](#impact--benefits)
8. [Team & About Us](#team--about-us)
9. [Usage / Demo](#usage--demo)
10. [Getting Started](#getting-started)
11. [Contact & Support](#contact--support)

---

## 📌 Overview

Kand Sanrakshan is an **IoT-enabled smart storage solution for onions**, aimed at reducing post-harvest losses by **30–40%**. It combines real-time sensing, automatic ethylene neutralization, dynamic temperature control, and remote monitoring to improve shelf life and minimize waste.

---

## ❗ Problem Statement

India experiences significant onion wastage during storage due to:

- **Sprouting & rotting** — 30–40% losses
- Conventional solutions (silica gel, alumina beads) are often **expensive or unsafe**
- **Cold storage** systems consume too much energy — not viable for small-scale farmers
- Massive **seasonal price fluctuations** due to supply inconsistency

Kand Sanrakshan tackles these issues with a sustainable, efficient alternative.

---

## 💡 Solution & Features

- **Ethylene Monitoring**: Uses ME3-C₂H₄ sensors connected to Arduino UNO + NodeMCU to detect gas levels in real time
- **Dynamic Temperature Control**: PWM-driven Peltier modules maintain optimal temperature
- **Ethylene Neutralization**: K₂MnO₄ mist (via ultrasonic mist maker) oxidizes ethylene to prevent sprouting
- **IoT & Remote Monitoring**: MQTT protocol enables farmers to track storage stats from anywhere
- **Alerts & Dashboard**: Receive notifications and view live readings (temperature, humidity, gas levels)

---

## 🧰 Technology Stack

| Component       | Technology / Device                     |
| --------------- | --------------------------------------- |
| Microcontroller | Arduino UNO, NodeMCU                    |
| Sensor          | ME3-C₂H₄ ethylene sensor                |
| Cooling         | Peltier modules                         |
| Mist System     | Ultrasonic mist maker + K₂MnO₄ solution |
| Communication   | MQTT protocol (IoT)                     |
| Front-end / UI  | Dashboard + web interface               |

---

## 🔄 How It Works

1. **Ethylene Detection**  
   Sensors continuously monitor the storage environment for ethylene levels.
2. **Smart Response**  
   When ethylene goes above a threshold, the system triggers the misting mechanism.
3. **Neutralization**  
   The mist generated (from K₂MnO₄ solution) oxidizes ethylene, preventing sprouting and decay.
4. **Temperature Regulation**  
   Peltier modules adjust power (via PWM) to maintain ideal temperature with minimal energy usage.
5. **Remote Monitoring & Alerts**  
   Data is sent via MQTT to the dashboard. Farmers can view readings and get notifications.

---

## 📊 Project Progress

| Module                | Completion |
| --------------------- | ---------- |
| Hardware Prototype    | 75%        |
| Dashboard Development | 90%        |
| IoT Integration       | 60%        |
| Field Testing         | 40%        |

---

## 🌱 Impact & Benefits

- **Economic**: Reduces losses by ~30–40%, boosting farmer revenue
- **Environmental**: Replaces toxic chemicals with safer, eco-friendly solutions
- **Social**: Empowers small farmers with affordable tech
- **Technological**: Leverages IoT, automation, and real-time analytics

---

## 👥 Team & About Us

**Tech-Teerandaz** is a team of passionate innovators competing in **Smart India Hackathon 2025**. Our mission: to build sustainable, tech-driven solutions for agricultural challenges.

Kand Sanrakshan is our flagship crop-preservation project aimed at combating post-harvest onion losses.

---

## 🎬 Usage / Demo

- Navigate to the **Live Dashboard** to see metrics like ethylene level, temperature, humidity, pump status, etc.
- Use the **“Login / Sign Up”** forms to access user-specific dashboard and alerts.

---

## 🛠️ Getting Started (for Contributors & Deployers)

1. **Clone the repository**
   ```bash
   git clone https://github.com/YourUsername/Kand-Sanrakshan.git
   cd Kand-Sanrakshan
   ```
