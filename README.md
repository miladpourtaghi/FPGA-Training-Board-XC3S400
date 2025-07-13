# FPGA Training / Breakout Board — XC3S400-4PQ208C

An educational FPGA breakout board based on the **Xilinx Spartan-3 XC3S400-4PQ208C (208-pin PQFP)**.  
This board was designed with **maximum flexibility and clarity for learning, prototyping, and testing FPGA projects**.  
The design provides clean access to almost all FPGA IO pins while also offering integrated RS232, VGA output, user LEDs, and configuration mode selection.

---

## 🎯 Project Overview

This board is intended as a **training platform** for students, engineers, or hobbyists to practice:
- FPGA architecture (Xilinx Spartan-3)
- HDL development (VHDL / Verilog)
- VGA output for basic image processing projects
- UART / RS232 communication
- GPIO control
- Practical debugging using onboard LEDs

The layout is designed with a focus on clarity, accessibility, and a clean logical structure suitable for learning environments.

> ⚠️ **Note:** This project is fully designed in **Altium Designer** but has not been fabricated yet.

---

## 🛠️ Hardware Specifications

### ✅ Key Features:
- **FPGA:** Xilinx Spartan-3 XC3S400-4PQ208C (208-pin PQFP)
- **Programming Options:** JTAG (2.54mm header)
- **Clock:** 50 MHz oscillator
- **Power Input:** 5V via USB or external
- **Breakout Headers:**  
    - **Nearly all I/O pins routed to 2.54mm headers** for maximum flexibility
    - Suitable for direct wiring to breadboards or external modules
- **Communication:**
    - **RS232 port** via **MAX232 IC** (DB9 connector)
- **Display Output:**
    - **VGA connector** routed directly to FPGA IOs (for basic video signal experiments)
- **User LEDs:**
    - **10 independent LEDs** connected to separate FPGA IO pins
    - Each LED connection includes a **jumper (Enable/Disable):**
        - **Enable**: LED connected for visual feedback
        - **Disable**: IO fully free for general-purpose use

---

### 🔧 Configuration Mode Selection (M0 / M1 / M2)
The board includes **three jumpers (M0, M1, M2)** for selecting the FPGA configuration mode:
- **JTAG**
- **Master Serial**
- **Slave Serial**

Easily selectable via jumper headers.

---

## 📐 Aesthetic Design Consideration

The placement of the FPGA (XC3S400) on the PCB was intentionally chosen with attention to **visual harmony**, following proportions approximating the **Golden Ratio (φ ≈ 1.618)** between functional zones.  
This subtle design choice aims to reflect a balance between technical functionality and visual clarity, aligning with the belief that engineering and design aesthetics can complement each other.

---

## 📂 Repository Structure

hardware
├── PCB
│ ├── FPGA_Board.PrjPcb
│ └── FPGA_Board.PcbDoc
└── schematics
├── FPGA_Board.pdf
└── FPGA_Board.SchDoc

doc
├── Datasheet FPGA XC3S400.pdf
└── Projektbeschreibung_DE.md

image
├── PCB 3D.jpg
└── PCB.jpg
