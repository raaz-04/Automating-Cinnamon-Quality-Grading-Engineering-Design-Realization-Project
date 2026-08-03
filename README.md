<div align="center">

# 🌿 Integrated Precision Cinnamon Processor (IPCP)

### An Automated Cinnamon Quill Grading System

An embedded system that automates the grading of export-quality cinnamon quills by accurately measuring their **diameter** and **weight**, eliminating manual measurements and improving grading consistency.

<p align="center">
  <img src="images/WhatsApp Image 2026-07-31 at 17.44.58.jpeg" width="900">
</p>

![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![CAD](https://img.shields.io/badge/CAD-SolidWorks-orange)
![PCB](https://img.shields.io/badge/PCB-Altium%20Designer-red)
![Display](https://img.shields.io/badge/Display-OLED-green)

</div>

---

# 📖 Overview

The **Integrated Precision Cinnamon Processor (IPCP)** was developed for the **Engineering Design and Realization** module to automate the grading of export-quality cinnamon quills.

Traditional grading methods rely on manual measurements, making the process time-consuming and susceptible to inconsistencies. IPCP provides a contactless, automated solution that accurately measures key physical properties and determines the corresponding export grade.

The system integrates embedded electronics, precision sensing, mechanical design, and custom software into a single automated platform.

---

# ✨ Features

- 🌿 Automatic cinnamon grading
- 📏 Diameter measurement with **0.4 mm precision**
- ⚖ Weight measurement using dual load cells
- ⚙ Automated linear motion system
- 📺 OLED display interface
- 🎛 Button-controlled operation
- 🔋 ESP32-based embedded controller
- 📦 Custom-designed enclosure
- 💻 Custom PCB designed in Altium Designer

---

# 🛠 Hardware Components

| Component | Description |
|-----------|-------------|
| ESP32-WROOM-32D | Main Controller |
| HX711 | Load Cell Amplifiers |
| Load Cells | Weight Measurement |
| Stepper Motor | Linear Motion |
| Stepper Motor Driver | Motor Control |
| OLED Display | User Interface |
| Push Buttons | User Input |
| Custom PCB | Signal & Power Distribution |

---

# ⚙ System Architecture

```text
                Cinnamon Quill
                       │
                       ▼
          Mechanical Positioning System
                       │
      ┌────────────────┴────────────────┐
      │                                 │
      ▼                                 ▼
Diameter Measurement             Weight Measurement
      │                                 │
      └──────────────┬──────────────────┘
                     ▼
                  ESP32
                     │
      ┌──────────────┼───────────────┐
      ▼                              ▼
 OLED Display                Stepper Motor Driver
                                    │
                                    ▼
                              Stepper Motor
```

---

# 💻 Software & Design Tools

- Altium Designer
- SolidWorks
- Arduino IDE
- ESP32 Framework

---

# 📷 Project Gallery

## Complete Prototype

The assembled IPCP prototype with the mechanical grading platform.

<p align="center">
<img src="images/WhatsApp Image 2026-07-31 at 17.44.58.jpeg" width="850">
</p>

---

## Circuit Schematic

Complete electrical schematic designed in Altium Designer.

<p align="center">
<img src="images/WhatsApp Image 2026-07-01 at 11.56.24.jpeg" width="900">
</p>

---

## PCB Design

Custom PCB designed in Altium Designer.

<p align="center">
<img src="images/WhatsApp Image 2026-07-04 at 14.56.26.jpeg" width="750">
</p>

---

# 🚀 Working Principle

1. Place the cinnamon quill on the grading platform.
2. The stepper motor positions the measurement mechanism.
3. Optical sensing determines the quill diameter.
4. Dual load cells measure the weight.
5. The ESP32 processes the sensor data.
6. The export grade is calculated.
7. The result is displayed on the OLED screen.

---

# 🔄 Development Workflow

```text
Problem Identification
          │
          ▼
Requirement Analysis
          │
          ▼
Mechanical Design
          │
          ▼
Circuit Design
          │
          ▼
PCB Design
          │
          ▼
Firmware Development
          │
          ▼
Prototype Assembly
          │
          ▼
Calibration
          │
          ▼
Testing & Validation
          │
          ▼
Final Prototype
```

---

# 📁 Repository Structure

```
Integrated-Precision-Cinnamon-Processor
│
├── README.md
├── LICENSE
├── images
│   ├── WhatsApp Image 2026-07-31 at 17.44.58.jpeg
│   ├── WhatsApp Image 2026-07-01 at 11.56.24.jpeg
│   └── WhatsApp Image 2026-07-04 at 14.56.26.jpeg
│
├── Firmware
│
├── PCB
│
├── CAD
│
├── Documentation
│
└── BOM
```

---

# 🎯 Project Outcomes

- Automated cinnamon grading
- Contactless measurement system
- Improved grading consistency
- Reduced manual effort
- Faster quality assessment
- Modular embedded hardware design

---

# 🔮 Future Improvements

- Machine vision for defect detection
- Wireless data logging
- Cloud connectivity
- Touchscreen interface
- Rechargeable battery operation
- Automatic report generation
- Mobile application support

---

# 🤝 Team

Developed for the **Engineering Design & Realization** module.

**Team Scope**
- Subodha pieris
- Ransara Maldeniya
- Rasula Geesara
- Nayanajith Ranasinghe
- Dulen Sandiw

Special thanks to our project mentors and department lecturers for their continuous guidance and support throughout the project.

---

# 📄 License

This project is licensed under the MIT License.

---

<div align="center">

### ⭐ If you found this project interesting, consider giving it a star!

**Designed • Built • Programmed • Tested**

🌿 **Engineering Design & Realization Project**

</div>
