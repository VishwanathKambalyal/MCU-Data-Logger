# 📌 MCU Data Logger

![Project Banner](https://github.com/VishwanathKambalyal/MCU-Data-Logger/blob/main/images/3d%20mixed%20view.png)

## 📖 Overview

MCU Data Logger is a **hardware-based data logging system** designed to record and store data efficiently. The system is built using the **ATmega328P-AU microcontroller**, **24LC1025 EEPROM**, and **DS1337 RTC** for precise timekeeping. The hardware is designed in **KiCad 9**, with both **2-layer and 4-layer PCB** options.

### 🔹 Key Components

- **🖥️ ATmega328P-AU (MCU)**
  - Serves as the main processing unit.
  - Handles data acquisition, processing, and communication.
  - Supports multiple communication protocols (UART, SPI, I2C).

- **💾 24LC1025 EEPROM (I2C Storage)**
  - Provides non-volatile memory for data storage.
  - Communicates via the I2C protocol.
  - Can store up to **1 Mbit** of data.

- **⏳ DS1337 Real-Time Clock (RTC)**
  - Maintains accurate timestamps for logged data.
  - Operates using the I2C protocol.
  - Supports alarms and timekeeping even in power-off conditions.

- **🔌 Power System**
  - Operates on a **5V** power supply.
  - Includes **ground (GND) connections** for circuit stability.

- **📡 Communication Interfaces**
  - **UART (Tx, Rx)** for serial communication.
  - **SPI (SCK, MOSI, MISO, RESET)** for high-speed data transfer.
  - **I2C (SDA, SCL)** for sensor and memory communication.

- **🖲️ General-Purpose Input/Output (GPIO)**
  - Available on **D2-D8** pins.
  - Can be used for external sensors or control signals.

---

## 🔧 Features

- ✅ **Microcontroller**: ATmega328P-AU
- ✅ **Memory Storage**: 24LC1025 EEPROM (I2C)
- ✅ **Real-Time Clock (RTC)**: DS1337 (I2C)
- ✅ **Interfaces**:
  - **UART**: Tx, Rx
  - **SPI**: SCK, MOSI, MISO, RESET
  - **I2C**: SDA, SCL
- ✅ **Power Supply**: 5V
- ✅ **GPIOs**: D2-D8 for peripheral connections
- ✅ **Compact PCB Design**: 2-layer and 4-layer versions

---

## 📷 Project Images

### 🔹 Schematic Diagram

![Schematic Diagram](Images/schematic.png)

### 🔹 PCB Designs

| 2-Layer PCB                          | 4-Layer PCB                          |
| ------------------------------------ | ------------------------------------ |
| ![2-Layer PCB](https://github.com/VishwanathKambalyal/MCU-Data-Logger/blob/main/images/2_Layer_PCB.png)  | ![4-Layer PCB]https://github.com/VishwanathKambalyal/MCU-Data-Logger/blob/main/images/4_Layer_PCB.png)  |

### 🔹 3D PCB Views

| Top View                             | Bottom View                          |
| ------------------------------------ | ------------------------------------ |
| ![Top View](https://github.com/VishwanathKambalyal/MCU-Data-Logger/blob/main/images/3d%20Front%20view.png)       | ![Bottom View](https://github.com/VishwanathKambalyal/MCU-Data-Logger/blob/main/images/3d%20bottom%20view.png)  |

---

## 🔌 How to Use

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/VishwanathKambalyal/MCU-Data-Logger.git
```
###2️⃣ Open Hardware Files in KiCad 9
Navigate to the Hardware folder.
Open the schematic (.sch) and PCB (.kicad_pcb) files.

###3️⃣ Customize & Manufacture
Modify the PCB design if required.
Generate Gerber files for PCB fabrication.

##📜 License
This project is licensed under the MIT License – you are free to use, modify, and distribute it as needed.
