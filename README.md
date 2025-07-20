# Arduino Uno PCB - Altium Designer Project

This repository contains a custom **Arduino Uno PCB design** created with **Altium Designer**.  
It is intended for educational and prototyping purposes, allowing hobbyists, students, and engineers to design and manufacture their own Arduino Uno-compatible board.

## Project Overview

- **Project Name**: Arduino Uno Custom PCB  
- **Software Used**: Altium Designer  
- **PCB Type**: 2-layer board (standard FR4)  
- **Purpose**: Learning, prototyping, and hardware customization

## Features

- Fully compatible with Arduino Uno R3 pinout  
- Based on ATmega328P microcontroller  
- USB to UART bridge (CH340 or similar, optional in design)  
- Standard Arduino headers for shields and expansions  
- Power input options: USB or external barrel jack  
- On-board reset button and LEDs (Power & User LED)

## Repository Structure

| Folder/File         | Description                             |
|--------------------|-----------------------------------------|
| **/ArduinoUno_PCB.PrjPcb** | Main Altium project file          |
| **/Schematic/**     | All schematic sheets                    |
| **/PCB/**           | PCB layout files (Top/Bottom layers)    |
| **/Outputs/**       | Fabrication outputs (Gerber, NC Drill) |
| **/Library/**       | Custom components and footprints        |

## How to Use

1. Open the project in **Altium Designer**.
2. Review or modify the schematic if needed.
3. Open the PCB layout and make adjustments as desired.
4. Generate fabrication files (Gerber, BOM, etc.) for manufacturing.
5. Assemble and test your custom Arduino Uno board.

## License

This project is open-source and shared for learning purposes.  
Feel free to use, modify, and distribute with proper attribution.

---

### Author

**Keyhan Salehi**  
[GitHub Profile](https://github.com/KeyhanSalehi)
