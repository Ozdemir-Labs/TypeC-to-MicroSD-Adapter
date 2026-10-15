# TypeC-to-MicroSD-Adapter

Welcome to the official repository of the Type-C to Micro SD Card Reader, meticulously designed and developed by **Ozdemir Labs**. This hardware project features a highly stable, zero-DRC-error custom PCB layout, providing a compact and robust data transfer solution for modern computers, smartphones, and professional tech workstations.

---

## 📸 Project Visuals

Here are the complete design stages and technical schematics of the hardware:

### 1. 3D Render View
![Project 3D Render](images/3d_render.png)

### 2. 2D Top/Bottom Layout
![Project 2D Layout](images/2d_layout.png)

### 3. Schematic Diagram
![Project Schematic](images/schematic.png)

---

## 🛠️ About the Designer & Creator

Hi there! I am **Abdullah Özdemir**, the technical mind behind **Ozdemir Labs** and the manager of **Özdemir Teknik Bilgisayar**. 

I am a certified computer technician with extensive training and practical experience in hardware troubleshooting, computer assembly, software configuration, operating system installations, and small-scale electronic diagnostic services. 

### My Journey & Expertise:
*   **Computer Repair & Assembly:** Advanced experience in building desktop setups, diagnostic methodologies, and component maintenance.
*   **Software & Flashing:** Deep knowledge in operating system deployment, bootloader management, and software configuration tools.
*   **PCB Design Journey:** Although I am **new to the field of PCB design**, I adapt incredibly fast to industrial design guidelines. I approach hardware routing with high discipline, mathematical precision, and an eye for physical reliability.

Despite being new to advanced electronic design, my ambition is backed by strong market insights and high technical aptitude. **Ozdemir Labs** aims to combine traditional heavy industrial knowledge with modern technology to deliver commercial-grade hardware kits and servicing tools.

---

## ⏳ Project Background & Effort

This project is the result of true dedication and precision engineering. I spent **exactly 10 hours** working on this specific iteration, moving from component research to circuit topology, and finally solving multi-layered routing paths. 

The original goal was to build a clean, production-ready tool. After refining trace spacing and running strict design verifications, the design successfully passed the **DRC (Design Rule Check) with 0 errors**, ensuring the PCB is fully optimized for professional manufacturing and flawless soldering.

---

## ⚙️ Technical Specifications

This compact adapter translates high-speed Micro SD card data into standard USB communication protocols using minimum components for maximum durability:

*   **Main Controller (MCU/IC):** `GL823K` (SSOP-16 package for easy manual soldering and high thermal stability).
*   **Input Interface:** `USB Type-C 16-Pin (DIP)` (Equipped with robust structural mechanical legs for workplace durability).
*   **Card Interface:** `Standard Micro SD / TF Card Socket (SMD/DIP Combo)`.
*   **Clock Frequency:** `12MHz Crystal Oscillator` (HC-49S package).
*   **Filtering & Noise Reduction:** `100nF (104) Non-Polarized Ceramic Capacitor` (Effectively absorbs voltage ripples to prevent data drops during heavy transfers).
*   **Host Detection Resistance:** Dual `5.1kΩ resistors` connected to CC1/CC2 lines for automatic host device enumeration.

---

## 📦 Commercial Options & Demand

Based on market analysis, computer repair centers and digital creators suffer continuously from cheap, overheating dongles that disconnect during high-volume file transfers. By introducing an optimized **100nF decoupling capacitor** and heavy copper paths, this design eliminates communication failures.

We are currently evaluating this board for the following releases:
1.  **Bare PCB Option:** For electronics hobbyists who want to source and solder components themselves.
2.  **Disassembled Kit (DIY Kit):** Shipped with the custom PCB and all necessary high-grade components ready for assembly.

---

## 📜 License & Contributions
Developed by **Abdullah Özdemir / Ozdemir Labs**. All rights reserved. For commercial manufacturing licensing or custom hardware collaboration inquiries, feel free to open an issue or contact me via my GitHub profile.
