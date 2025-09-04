# Composite Ski Bending Study

## Project Overview  
This project focuses on the mechanical behavior of a composite ski subjected to three-point bending. The main goal is to analyze the deflection of the ski under different loading conditions and compare numerical predictions with experimental results. The study is part of the academic curriculum in **Mechanical Engineering at ENSEM**.  

Three different modeling approaches were considered:  
1. **1D Beam Model**  
2. **Mid-plane Model**  
3. **3D Geometry Model**  

I realised this work with two teammates. 
In this work, I decided to focused on the **3D geometry** of the ski.  

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
- /geometry/ → CAD files of the ski (3D geometry Catia)
- /simulation/ → Numerical models and results (Abaqus or equivalent)
- /final presention/ → Presentation support made for the final oral.

---

## How to Use  
1. Open the geometry files in your favorite CAD/FEA software.  
2. Apply boundary conditions and load cases as you wish. 
3. Compare numerical deflections with the provided experimental data.  
4. Use the results to validate or refine the material model and try to approach the experimental results!

---

## Academic Context  
This project was conducted as part of the **Mechanical Engineering program at ENSEM**. It contributes to the understanding of composite structures under flexural loading and their modeling at different levels of complexity.  

