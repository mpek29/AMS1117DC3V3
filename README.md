# AMS1117DC3V3

## 🚀 Overview
![Main Preview](assets/img/main.png)

An open-source reverse-engineered version of the AMS1117 3.3V DC-DC buck converter module, based on the original component available [here](https://fr.aliexpress.com/item/1005006783027108.html).  
This project aims to provide insights into DC-DC voltage regulation and offer a customizable alternative for power management in embedded systems.

## 🎯 Purpose
- 🔍 **Reverse engineering**: Understanding the design and functionality of the AMS1117-based voltage regulator.
- 🛠️ **Skill development**: Enhancing expertise in PCB design and power electronics.
- 🔄 **Future adaptation**: Leveraging this knowledge to develop custom voltage regulation solutions for embedded applications.

## 📝 Features Comparison: Original vs. Reverse-Engineered

| Feature            | Original Module | Reverse-Engineered Version |
|--------------------|----------------|---------------------------|
| 🖥️ PCB Design        | Proprietary     | Open-source & customizable |
| 🔌 Input Voltage    | 4.8V - 15V       | 4.8V - 15V |
| ⚡ Output Voltage   | 3.3V (fixed)     | 3.3V (fixed) |
| 📦 Max Current     | 1500 mA            | 1500 mA |
| 🏷️ Regulator Chip  | AMS1117-3.3      | AMS1117-3.3 |
| 👐 Mechanical Drawing  | <img src="images/original_pcb.png" width="300" height="300"> | <img src="images/reversed_pcb.png" width="300" height="300"> |
| 📝 Reverse-Engineered Schematic | N/A | <img src="images/reversed_sch.png" width="300" height="300"> |
| 📷 Photo             | <img src="images/original_3d_high.png" width="300" height="300"> | <img src="images/reversed_3d.png" width="300" height="300"> |

## 🛠️ How to Use
### 📌 Wiring Guide
| Pin  | Description |
|------|-------------|
| VIN  | Input Voltage (4.8V - 15V) |
| GND  | Ground |
| VOUT | Regulated 3.3V Output |

## 🌟 License
This project is open-source. Feel free to use, modify, and contribute! 🚀
