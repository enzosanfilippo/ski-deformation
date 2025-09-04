# Composite Ski Bending Study

## Project Overview  
This project focuses on the mechanical behavior of a composite ski subjected to three-point bending. The main goal is to analyze the deflection of the ski under different loading conditions and compare numerical predictions with experimental results. The study is part of the academic curriculum in **Mechanical Engineering at ENSEM**.  

Three different modeling approaches were considered:  
1. **1D Beam Model**  
2. **Mid-plane Model**  
3. **3D Geometry Model**  

In this work, the focus was placed on the **3D geometry** of the ski.  

---

## Methodology  

### Experimental Setup  
- The ski was placed on a three-point bending test bench with adjustable supports.  
- A hydraulic jack applied the load, with the pressure measured by a manometer (effective section: 14.5 cm²).  
- The ski deflection was measured using a calibrated laser device.  
- A cross-section of a second ski was used to measure exact dimensions and to observe material distribution.  

### 3D Model Implementation  
- Measurements of the ski were taken and transferred to the **3D model**.  
- The support points and the location of the hydraulic jack force were reproduced in the 3D geometry.  
- Different pressure values were applied in the simulation, corresponding to the experimental test cases.  
- The main output was the **deflection profile along the ski length**.  

### Comparison with Experiment  
- Simulated deflections were compared with experimental values for several loading conditions.  
- Potential sources of discrepancy were discussed, including:  
  - Simplifications in the 3D model,  
  - Assumptions on material properties (composite layup),  
  - Friction at supports,  
  - Non-linear effects due to large displacements.  

---

## Objectives  
- Evaluate the equivalent stiffness of the ski and its deflection behavior.  
- Determine whether classical beam theory remains valid under large displacements.  
- Highlight differences between simulation and experimental results.  

---

## Repository Structure  
