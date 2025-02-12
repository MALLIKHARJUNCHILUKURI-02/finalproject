# Implementation and Analysis of 6-Transistor SRAM Cell

## 📌 Project Overview
This project focuses on the **design, implementation, and analysis** of a **6-Transistor (6T) SRAM Cell** using **Cadence software** in **45-nanometer technology**. The study evaluates key parameters such as **power consumption, delay characterization, layout design, and area estimation**, providing insights into its performance and efficiency.

## 🚀 Features
- **Schematic Design:** Implemented using **Cadence Virtuoso**
- **Layout Design:** Optimized for **minimum area and parasitic effects**
- **Power Consumption Analysis:** Conducted under different transistor sizing scenarios
- **Delay Characterization:** Measured **read/write cycle times and access time**
- **Post-Layout Simulations:** Verified for **design rule checks (DRC) and layout vs schematic (LVS)**

## 🛠️ Technologies Used
- **Cadence Virtuoso** – For schematic capture and layout design
- **Cadence Spectre** – For circuit simulation
- **Assura DRC/LVS** – For design rule and layout verification

## 📂 Project Structure
```
6T-SRAM-Project/
│-- schematics/          # Schematic design files
│-- layouts/             # Layout design files
│-- simulations/         # Simulation results and waveform outputs
│-- documentation/       # Project report and findings
│-- README.md           # Project documentation
```

## 🎯 How to Run the Project
1. **Setup Cadence Environment:**
   - Load Cadence Virtuoso and set up the **gpdk45 library**.
2. **Open the Schematic:**
   - Navigate to the **schematics/** directory and open the **6T SRAM schematic** in Virtuoso.
3. **Run Pre-Layout Simulations:**
   - Use **Cadence Spectre** to analyze power and delay characteristics.
4. **Layout Design:**
   - Open **layouts/** in Virtuoso and verify using **DRC and LVS**.
5. **Post-Layout Simulations:**
   - Perform **power, area, and timing analysis** after layout verification.

## 📊 Results & Findings
- **Power Consumption:** Achieved **28nW** in optimized design.
- **Delay Analysis:** Measured **propagation delays** for different input conditions.
- **Area Estimation:** Optimized transistor sizing to reduce layout area.

## 🌟 Future Scope
- Compare **6T SRAM with alternative designs (4T, 8T)** for performance improvements.
- Implement **low-power optimization techniques** to reduce leakage power.
- Extend design for **16-bit SRAM array implementation**.

## 🤝 Contributors
- **B. Satya Suresh**
- **Ch. Mallikharjun Reddy**
- **P. Bhuvana Sri**
- **Guide: Dr. P. Lachi Reddy**

## 📜 License
This project is for **academic and research purposes only**.

## 📬 Contact
For any queries, feel free to reach out:
- **Mallikharjun Reddy Chilukuri** - https://github.com/MALLIKHARJUNCHILUKURI-02
- **Email:** mkreddychilukuri075@gmail.com
