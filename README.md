# Low-Power CMOS Temperature Sensor with Monte-Carlo Verified Analog Front-End

*The purpose of this project is to design a low-power CMOS temperature-sensing front-end with a digital on/off thermostat controller, verified for robustness using Monte Carlo and corner analysis.*

---

## Overview
This project implements a **CMOS temperature sensor** with a **digital thermostat control** for threshold-based switching. The analog front-end converts temperature variations into a voltage signal, which is then compared to a reference to generate a digital output. The design emphasizes **low-power operation** suitable for on-chip thermal monitoring in integrated circuits.

---

## Design Methodology
- Designed the **CMOS analog front-end** using standard **NMOS and PMOS devices**  
- Implemented a **digital on/off thermostat controller** for threshold detection  
- Performed **parametric analysis** to study circuit behavior under varying temperature and device parameters  
- Conducted **Monte Carlo simulations** to evaluate performance variations due to process mismatch  
- Verified robustness across **process corners (TT, FF, SS)**  

---

## Tools & Technologies
- **EDA Tool:** Cadence Virtuoso  
- **Simulator:** Spectre  
- **Design Domain:** CMOS Analog Circuit Design  
- **Concepts Used:** Temperature sensing, comparator-based control, low-power analog design, Monte Carlo analysis  

---

## Performance Metrics
- **Operating Temperature Range:** 0°C – 100°C  
- **Supply Voltage:** 1.8 V  
- **Output Sensitivity:** ~1–2 mV/°C (typical)  
- **Power Consumption:** Low static bias current  
- **Monte Carlo Analysis:** 50 runs; confirmed limited spread of output voltage  
- **Corner Simulations:** TT, FF, SS  

---

## Simulation & Verification
- Conducted **DC and transient simulations** to evaluate temperature response  
- Verified **digital output switching** at the defined threshold  
- Performed **Monte Carlo analysis** to ensure reliability under mismatch  
- Simulated **process corners** to check performance variation  

---

## Output Results
Simulation results demonstrate:
- Consistent analog output voltage proportional to temperature  
- Reliable digital thermostat switching at the threshold point  
- Limited variation under Monte Carlo analysis and process corners  

<!-- Add images of simulation plots -->
<!-- Example: ![Temperature Response](images/temp_response.png) -->

---

## How to Reproduce
1. Open the project in **Cadence Virtuoso**  
2. Launch **Spectre simulator**  
3. Set temperature sweep from **0°C to 100°C**  
4. Run **DC and transient simulations**  
5. Perform **Monte Carlo simulations** (50 runs)  
6. Conduct **process corner simulations** (TT, FF, SS)  
7. Observe analog output slope and digital switching output  

---

## Future Work
- Calibration for improved accuracy  
- Integration with **ADC for digital temperature readout**  
- Ultra-low-power optimization for IoT/SoC applications  
- Layout implementation and post-layout verification  

---

## Author
**Nischal Agarwal**  
Electronics and Communication Engineering  
Birla Institute of Technology, Mesra

