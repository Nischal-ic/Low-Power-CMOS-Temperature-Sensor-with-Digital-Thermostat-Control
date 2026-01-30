# Low-Power CMOS Temperature Sensor with Digital Thermostat Control

*The purpose of this project is to design and simulate a low-power CMOS temperature-sensing front-end with a digital on/off thermostat controller for on-chip thermal monitoring applications.*

---

## Introduction
This project presents a **CMOS-based temperature sensor** designed using **analog front-end circuits** in Cadence Virtuoso. The sensor converts temperature variations into a voltage signal, which is processed by a **digital thermostat controller** to generate an on/off control output. The design emphasizes **low-power operation**, making it suitable for **on-chip thermal monitoring** in integrated circuits.

---

## Design Methodology
- Designed a **CMOS temperature-sensing front-end** using basic analog building blocks  
- Utilized temperature-dependent MOS characteristics for sensing  
- Implemented a **threshold-based digital controller** for temperature switching  
- Optimized biasing for **low static power consumption**  
- Verified robustness using **corner and Monte Carlo analysis**

---

## System Description
- The analog front-end generates a voltage proportional to temperature  
- A reference threshold determines the thermostat switching point  
- Digital output switches ON/OFF based on temperature comparison  
- Suitable for thermal protection and temperature-aware control systems  

---

## Tools & Technologies
- **EDA Tool:** Cadence Virtuoso  
- **Simulator:** Spectre  
- **Design Domain:** CMOS Analog Front-End Design  
- **Concepts Used:** Temperature sensing, biasing, comparators, low-power design  

---

## Performance Metrics
- **Operating Temperature Range:** 0°C – 100°C  
- **Supply Voltage:** 1.8 V  
- **Output Sensitivity:** ~1–2 mV/°C (typical)  
- **Power Consumption:** Low static bias current operation  
- **Variability Analysis:** Monte Carlo and process corner simulations performed  

---

## Simulation & Verification
- Performed **DC and transient simulations** across temperature range  
- Conducted **Monte Carlo analysis** to study mismatch effects  
- Verified operation under **process corners (TT, FF, SS)**  
- Analyzed temperature-dependent output slope and switching behavior  

---

## Output Results
Simulation results demonstrate a consistent temperature-dependent voltage response and reliable digital switching behavior at the defined threshold. Monte Carlo and corner analyses confirm acceptable robustness against process and device variations.

<!-- Add simulation plots here -->
<!-- Example:
![Temperature Response](images/temp_response.png)
-->

---

## How to Reproduce
1. Open the design in **Cadence Virtuoso**  
2. Launch **Spectre simulation environment**  
3. Set temperature sweep from **0°C to 100°C**  
4. Run DC and transient analyses  
5. Perform corner and Monte Carlo simulations  
6. Observe analog output slope and digital control signal  

---

## Future Work
- Calibration for improved accuracy  
- Integration with **ADC for digital temperature readout**  
- Ultra-low-power optimization for IoT applications  
- Layout implementation and post-layout verification  

---

## Author
**Nischal Agarwal**  
Electronics and Communication Engineering  
Birla Institute of Technology, Mesra
