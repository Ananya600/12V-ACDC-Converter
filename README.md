# 12V AC-DC Converter

A compact, reliable hardware design that converts an alternating current (AC) input into a regulated 12V direct current (DC) output. This repository contains the complete schematic capture and PCB layout designed using **KiCad 7.0+**.

---

## 🚀 Features & Overview

This board is designed to serve as a general-purpose, low-voltage power supply module. It takes a low-voltage AC input (typically fed from a step-down mains transformer) and performs the following stages:
1. **Rectification:** Converts the AC waveform into a pulsating DC waveform using a diode bridge rectifier.
2. **Filtering:** Smooths out the voltage ripples using high-capacity electrolytic filtering capacitors.
3. **Regulation:** Drops and stabilizes the voltage down to a steady 12V DC output suitable for driving microcontrollers, relays, fans, or small DC motors.

---

## 📂 Repository Structure

The repository is organized with the standard KiCad project file hierarchy:

```text
├── ACtoDCconverter.kicad_pro       # Main KiCad project configuration file
├── ACtoDCconverter.kicad_sch       # Schematic diagram detailing the circuit design
├── ACtoDCconverter.kicad_pcb       # Complete Printed Circuit Board (PCB) layout design
├── ACtoDCconverter.kicad_prl       # Project local settings (window placement, display options)
├── _autosave-ACtoDCconverter.kicad_sch # Automated schematic autosave recovery file
└── ACtoDCconverter-backups/        # Directory containing automated ZIP backups by KiCad
```

## 🛠️ How to Open and Use the Project

### Prerequisites

You must have **KiCad 7.0** or a newer version installed on your machine to guarantee full file compatibility. Download it for your operating system from the [Official KiCad Website](https://www.kicad.org/).

### Setup Instructions

1. **Clone the Repository:**
```
git clone [https://github.com/Ananya600/12V-ACDC-Converter.git](https://github.com/Ananya600/12V-ACDC-Converter.git)
cd 12V-ACDC-Converter
```



2. **Open the Project:**
* Launch KiCad.
* Click on **File > Open Project...**
* Navigate to the cloned folder and select `ACtoDCconverter.kicad_pro`.


3. **Explore Design Assets:**
* Double-click the **Schematic Editor** icon to view the circuit configurations, component footprints, and electrical connections.
* Double-click the **PCB Editor** icon to inspect the board trace routing, copper fills, component placements, and layer stack-ups.



---

## 📜 License

This project is open-source hardware. Feel free to clone, modify, build, and adapt it for your own commercial or hobbyist power supply applications.

```

```
