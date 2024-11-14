# IoT Soil PH and Moisture Mapping module 
> A soil pH and moisture logging module.
<img src="https://github.com/user-attachments/assets/a2a56503-3629-4138-bb58-be04060bd364" />

## 🚩 Table of Contents

- [Project Description](#-project-description)
- [Schematics](#-schematics)
- [PCB Design Properties and Specifications](#-pcb-design-properties-and-specifications)
- [Board Presentation](#-board-presentation)
- [Bill of Materials](#-bill-of-materials)
- [Version History](#-version-history)
- [Download Project Files](#-download-project-files)
- [Used By](#-used-by)
- [License](#-license)


##  Project Description 
This project aimed to develop a visual representation of soil moisture and pH across farmlands. We can do this by acquiring PH and Moisture data using suitable sensors. The module's location (later vision) will help establish a GPS waypoint on the farmland to help us understand which area of the farmland is being measured. GPS coordinates, soil moisture, and soil PH is collected and transmitted to a gateway.


## 🤖 Schematics?

The schematics are all on one sheet. The Sheet contains symbols and connections for a USB-C, ESP32-C3 Soc, RGB module, 2MB flash storage, terminal blocks, a buzzer, optocouplers, and 12V to 5V power converter

### IoT Soil PH and Moisture Mapping Schematic Sheet 1
This image is compressed. You can download the schematics in the Project files section below if you struggle with seeing certain details. Thanks!!
<img src="https://github.com/user-attachments/assets/b11934f4-bb2f-49ea-b43e-d20f67230e7f" />


## 🎨 PCB Design Properties and Specifications
| Category | Description |
| --- | --- |
| Board Thinkess | 1.6178 |
| Dimension | 80mm x 50mm  |
| Number of Layers |  4  |
| Soldermask | Black |
| Silkscreen | White |
| Mounting Holes | 4 |
| Edge Fillet size | 6mm |
| Impedance Profile (Antenna) | 50 |
| Impedance Profile (USB) | 90 |
| Minimum Hole Size  | 0.2mm |
| Maximum Hole Size | 7.62mm |

## 🐾 Board Presentation 
Below is the board in different views. To see areas of the board not shown below, please visit the Altium 365 project link. 
<img src="https://github.com/user-attachments/assets/d7cab1d6-857d-4f20-b2da-4b56aaad9e8a" />



## 🌏 Bill of Materials

| #  | Name                    | Description                             | Designator     | Revision Status | Quantity | Manufacturer          | Manufacturer Part Number       | Supplier    | Supplier Unit Price |
|----|--------------------------|-----------------------------------------|----------------|-----------------|----------|------------------------|--------------------------------|-------------|----------------------|
| 1  | Antenna                 | Antenna module                          | AE1            | Up to date      | 1        | Murata                | GRM1885C1H100JA01D            | Mouser      | 0.1                 |
| 2  | GRM1885C1H100JA01D      | Capacitor, 0.10uF, 6.3V                 | C1, C2         | Up to date      | 2        | Murata                | GRM1885C1H100JA01D            | Mouser      | 0.1                 |
| 3  | GRM033R60J104KE19D      | Capacitor, 10uF, 6.3V                   | C3, C4, C5, C6, C15 | Up to date | 5       | Murata                | GRM033R60J104KE19D            | Newark      | 0.008               |
| 4  | GRM188R60J106ME47D      | Capacitor, 10uF, 6.3V                   | C7, C9, C16    | Up to date      | 3        | Murata                | GRM188R60J106ME47D            | Newark      | 0.065               |
| 5  | C0805C226M9PACTU        | Capacitor, 22uF, 6.3V                   | C10, C11       | Up to date      | 2        | KEMET                 | C0805C226M9PACTU              | Digikey     | 0.21                |
| 6  | GRM188R71A225KE15D      | Capacitor, 2.2uF, 10V                  | C12, C13       | Up to date      | 2        | Murata                | GRM188R71A225KE15D            | Digikey     | 0.17                |
| 7  | GJM1555C1H3R3CB01D      | Capacitor, 3.3pF                        | C18, C19       | Up to date      | 2        | Murata                | GJM1555C1H3R3CB01D            | Digikey     | 0.1                 |
| 8  | PMEG6020AELRX           | Schottky Diode, 60V                     | D2             | Up to date      | 1        | Nexperia              | PMEG6020AELRX                 | Newark      | 0.115               |
| 9  | 16V Resetable Fuse       | Resettable Fuse                         | F1             | Up to date      | 1        | Murata                | BLM18PG121SN1D                | Digikey     | 0.1                 |
| 10 | W25Q16JVUXIQ            | Flash memory, 16Mb                      | IC1            | Up to date      | 1        | Winbond               | W25Q16JVUXIQ                  | Digikey     | 0.45                |
| 11 | TYPE-C-31-M-12          | USB Connector                           | IC2            | Up to date      | 1        | STMicroelectronics    | USBLC6-2SC6                   | Mouser      | 0.36                |
| 12 | USBLC6-2SC6             | Integrated Circuit                      | IC3            | Up to date      | 1        | STMicroelectronics    | USBLC6-2SC6                   | Mouser      | 0.36                |
| 13 | AMS1117-3.3             | Voltage Regulator                       | IC4            | Up to date      | 1        | AMS                   | AMS1117-3.3                   | Digikey     | 0.12                |
| 14 | LQW18AN2N2C80D          | Inductor, 2.2nH                         | L2             | Up to date      | 1        | Murata                | LQW18AN2N2C80D                | Mouser      | 0.18                |
| 15 | 150060VS75000           | LED Indicator                           | LED1           | Out of date     | 1        | Wurth Electronics     | 150060VS75000                 | Digikey     | 0.15                |
| 16 | PS1720P02               | Piezo Transducer                        | LS1            | Up to date      | 1        | TDK                   | PS1720P02                     | Arrow       | 0.0551              |
| 17 | 691322110002            | Header pins                             | P1-P7          | Up to date      | 7        | Wurth Electronics     | 691322110002                  | Digikey     | 0.44                |
| 18 | 691305140004            | Connector                               | P8             | Up to date      | 1        | Wurth Electronics     | 691305140004                  | Digikey     | 1.2                 |
| 19 | KSC1815YTA              | Transistor                              | Q1             | Up to date      | 1        | Fairchild            | KSC1815YTA                    | Digikey     | 0.05                |
| 20 | HCPL-181-00CE           | Optocoupler                             | Q2, Q3         | Up to date      | 2        | Broadcom Avago        | HCPL-181-00CE                 | Mouser      | 0.76                |
| 21 | RT0603FRE075K1L         | Resistor, 5.1K OHM                      | R1, R4, R5     | Up to date      | 3        | Yageo                 | RT0603FRE075K1L               | Digikey     | 0.018               |
| 22 | RC0402JR-07220RL        | Resistor, 220 OHM                       | R2             | Up to date      | 1        | Yageo                 | RC0402JR-07220RL              | Newark      | 0.045               |
| 23 | ERJ-2RKF1001X           | Resistor, 1K OHM                        | R6, R8         | Up to date      | 2        | Panasonic            | ERJ-2RKF1001X                 | Newark      | 0.004               |
| 24 | ERJ-3EKF1650V           | Resistor, 1.65K OHM                     | R7, R9         | Up to date      | 2        | Panasonic            | ERJ-3EKF1650V                 | Newark      | 0.006               |
| 25 | CRCW1206220RFKEA        | Resistor, 220 OHM                       | R11, R12       | Up to date      | 2        | Vishay               | CRCW1206220RFKEA              | Digikey     | 0.1                 |
| 26 | ERJ1GNF4700C            | Resistor, 470 OHM                       | R13, R14       | Up to date      | 2        | Yageo                 | RC0201FR-07470RL              | Newark      | 0.005               |
| 27 | B3F-1000                | Tactile Switch                          | SW1            | Up to date      | 1        | Omron                | B3F-1000                      | Newark      | 0.199               |
| 28 | ESP32C3                 | WiFi/BLE Module                         | U1             | Up to date      | 1        | Adafruit Industries   | 1655                          | Arrow       | 2.89                |
| 29 | 1655                    | Integrated LED                          | U2             | Up to date      | 1        | Adafruit Industries   | 1655                          | Arrow       | 2.89                |
| 30 | ABM8-40.000MHZ-10-1-U-T | Crystal, 40MHz                          | Y1             | Up to date      | 1        | Abracon              | ABM8-40.000MHZ-10-1-U-T       | Digikey     | 0.43                |
| 31 | ABM8-40.000MHZ-10-1-U-T | Crystal, 40MHz                          | Y2             | Up to date      | 1        | Abracon              | ABM8-40.000MHZ-10-1-U-T       | Digikey     | 0.43                |

- 
#### Altium 365 Project

``` sh
 https://oreofeoluwa-ayoola.365.altium.com/designs/28BCF5DB-3B28-4A5B-AA95-F2BDC21DAB44
```

## 💬 Version History
## 🍞 Download Project Files

- [Schematics](https://github.com/Oreoluwa-IVT/IoT-Soil-PH-and-Moisture-Mapping-module-Prototype-/blob/main/Altium%20Schematic%20Files.zip)
- [PCB Files](https://github.com/Oreoluwa-IVT/IoT-Soil-PH-and-Moisture-Mapping-module-Prototype-/blob/main/Altiium%20PCB%20Files.zip)
- [Gerber Files](https://github.com/Oreoluwa-IVT/IoT-Soil-PH-and-Moisture-Mapping-module-Prototype-/blob/main/GerberX2.zip)

## 📜 License
This software is licensed under the [MIT](https://github.com/nhn/tui.editor/blob/master/LICENSE) 
