# Turbine Casing CFD & FEM Analysis

This project presents a **virtual validation of a turbine casing**, combining **Computational Fluid Dynamics (CFD)** and **Finite Element Method (FEM)** simulations.  
The goal is to demonstrate a complete engineering workflow — from 3D modeling to structural verification — for turbomachinery components.

---

## 🧩 Project Overview

- **Component:** Turbine casing  
- **Objective:** Analyze the internal fluid flow and assess the structural response under realistic load conditions  
- **Tools Used:**  
  - *Siemens NX Simcenter* – CFD simulation  
  - *ANSYS 2025 R1* – Structural FEM analysis  
- **Working Fluid:** Air (incompressible)  
- **Boundary Conditions:** Inlet velocity and outlet pressure corresponding to nominal operating conditions

---

## 💨 CFD Analysis

The CFD analysis focused on the **velocity field and flow distribution** within the turbine casing.  
Main findings include:

- Maximum velocity of approximately **30 m/s** localized near the upper curvature region  
- Smooth flow distribution with minimal recirculation zones  
- Consistent behavior with the expected flow path for the given geometry  

**Figure – CFD Velocity Field (Absolute Velocity, m/s):**  
![CFD_Velocity_Field](CFD_Simulation/velocity_field.jpg)

---

## 🧱 FEM Analysis

A **static structural analysis** was performed to evaluate the casing’s integrity under representative loading conditions.  
The geometry was imported from the CFD model, meshed, and constrained according to realistic support points.

- Maximum **Von Mises stress:** ~6.9 MPa  
- The stress levels are **well below the yield strength** of typical casing materials  
- Uniform stress gradient indicating good stiffness and load distribution  

**Figures – Structural Results:**  
- ![FEM_Force_View](FEM_Simulation/vista_alto_Forze.jpg)  
- ![FEM_Stress_View](FEM_Simulation/vista_alto_VM.jpg)

---

## 🧾 Conclusions

- The casing shows a **robust structural response** under mechanical loading  
- The internal flow remains well-distributed, with no excessive velocity peaks  
- The results confirm the **feasibility and efficiency** of the component design  

---

## 🚀 Future Improvements

- **Mesh refinement** to capture finer flow features  
- **Thermo-mechanical coupling** to analyze temperature effects  
- **Parametric optimization** for geometry efficiency and weight reduction  

---

## 📂 Project Structure

