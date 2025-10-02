# Two-Stage Miller-Compensated Op-Amp (TSMC 180nm)

This repository contains the design and LTspice simulation of a **two-stage CMOS operational amplifier** implemented in **TSMC 180nm technology**.  
The design uses **Miller compensation** to ensure stability while maintaining high open-loop gain and wide bandwidth.

---

## 🔹 Project Specifications
- **Technology:** TSMC 180nm CMOS  
- **Architecture:** Two-stage op-amp with Miller compensation  
- **Key Results:**
  - DC Gain: ~70 dB  
  - Unity-Gain Bandwidth (UGB): ~101 MHz  

---

## 🔹 Why Two-Stage Op-Amps?
Two-stage op-amps are widely used in analog and mixed-signal circuits because they offer:  
- High open-loop gain (useful for precision applications)  
- Capability to drive capacitive loads  
- Wide output voltage swing  
- Stable operation with Miller compensation  

---

## 🔹 Repository Contents
- `miller_2stage.asc` → Two-stage op-amp schematic (LTspice)  
- `.gitignore` → Ignores LTspice simulation files (`.raw`, `.log`, `.bak`, `.tmp`)  
- `README.md` → Project documentation  

---

## 🔹 How to Use
1. Open the `.asc` and include the given tsmc180nm text file in **LTspice**  
2. Run **AC Analysis** to verify gain and UGB  
3. Adjust transistor sizing, bias current, or compensation capacitor to explore performance trade-offs  

---

## 🔹 Results
- Achieved **70 dB gain** with **~101 MHz UGB**  
- Stability ensured with **Miller compensation**  
- Suitable for analog front-ends and precision circuits  

---
