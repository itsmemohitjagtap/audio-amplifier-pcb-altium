# Audio Amplifier Circuit V1.0

## 📌 Project Overview

This project is a **PCB design for an Audio Amplifier Circuit**, built using the **LM386** audio amplifier IC. The design includes basic tone control using bass, gain, and volume settings. It is suitable for learning:

* Analog circuit PCB design
* Schematic to PCB workflow in Altium
* DRC-compliant layout practices
* Clean analog signal routing

This project is a part of my ongoing PCB design practice using **Altium Designer 25.2.1**.

## 🎯 Features

* Operates on low voltage (via VCC input)
* Drives a speaker or audio output device with gain control
* Includes potentiometers for **Bass**, **Gain**, and **Volume**
* Compact and functional layout
* Fully compliant with **Design Rule Check (DRC)**

## 🧠 Learning Outcomes

* Analog component placement and signal flow understanding
* Schematic capture and component annotation
* PCB routing in Altium Designer with attention to analog paths
* Creation of documentation (schematic, PCB print, netlist)

## 🗂️ Files Included

| File Name             | Description                                     |
| --------------------- | ----------------------------------------------- |
| `Audio_amplifier.pdf` | Complete schematic and PCB layout documentation |
| `schema.SchDoc`       | Altium schematic file (not uploaded)            |
| `PCB1.PcbDoc`         | Altium PCB layout file (not uploaded)           |
| `*.PrjPcb`            | Altium project file (not uploaded)              |

## 🔩 Components Used

* **LM386** – Low Voltage Audio Power Amplifier (U1)
* **Potentiometers** – For Gain, Bass, and Volume control
* **Capacitors** – C1 to C9 for coupling, bypassing, and filtering
* **Resistors** – R4, R5 for gain tuning
* **Connectors** – `J1`, `J2` for audio I/O, `P1` for power input

## 🖥️ Software Used

* **Altium Designer 25.2.1**

## 🔧 How It Works

* The **LM386** receives an audio signal via `J1`, amplifies it, and sends the output to `J2`.
* The **Bass**, **Gain**, and **Volume** controls adjust the tone and output level.
* Passive components ensure clean power supply filtering and signal coupling.
* The design follows best practices for analog audio PCB layout.

 🧑‍💻 Designed By

**Mohit Jagtap**  
Electronics & Telecommunication Engineering  
Dr. D. Y. Patil Institute of Engineering Management and Research, Akurdi, Pune

