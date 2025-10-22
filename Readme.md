# Multi-Sensitivity Soft Tactile Sensor using Flexible Mechanical Metamaterials

![COMSOL](https://img.shields.io/badge/Simulation-COMSOL%20Multiphysics-blue)
![CAD](https://img.shields.io/badge/CAD-SolidWorks-orange)
![Material](https://img.shields.io/badge/Material-TPU%20(A85)-green)
![IITRPR](https://img.shields.io/badge/IIT-Ropar-yellow)

---

## Project Overview

**Project Title:** Implementation of Flexible Mechanical Metamaterials Enabling Soft Tactile Sensors with Multiple Sensitivities at Multiple Force Sensing Ranges  
**Course Code:** CP302 — Honours Project  
**Institution:** Indian Institute of Technology Ropar  
**Department:** Mechanical Engineering  

**Team Members:**  
- **Rahul Yadav** — 2022MEB1334  
- **Sumer Mohan Singh Bassi** — 2022MEB1351  

**Supervisor:** Dr. Prabhat K. Agnihotri  

---

## Abstract

This project focuses on developing a **Multi-Sensitivity Soft Tactile (MST)** sensor using **flexible mechanical metamaterials**.  
The goal is to design and simulate a sensor capable of providing **multiple sensitivities across different force ranges**, overcoming the limitations of traditional single-sensitivity tactile sensors.

The sensor employs a **heterogeneous multi-layered metamaterial structure** with tunable stiffness properties, integrated with a **magnetic-based transduction mechanism** for force measurement.  
Simulations are conducted using **COMSOL Multiphysics**, combining *Solid Mechanics*, *Magnetic Fields*, and *Deformed Geometry* modules to model the mechanical and magnetic coupling behavior.

---

## Objectives

- Develop a mathematical and simulation framework for multi-sensitivity tactile sensing  
- Model a multi-layer metamaterial structure with programmable stiffness  
- Validate sensitivity and force range using multiphysics simulations  
- Demonstrate **step-by-step locking behavior** in a hierarchical structure  
- Prepare for future physical prototyping using TPU 3D printing  

---

## Methodology Summary

### 1. Mathematical Modeling
- Derived sensitivity equations based on **magnetic field variation with force**  
- Modeled metamaterial layers as **spring systems in series**  
- Established **stiffness hierarchy condition** for sequential deformation  

### 2. Simulation Framework
Implemented in **COMSOL Multiphysics** using:
- **Solid Mechanics Module:** Simulate deformation of TPU-based metamaterial  
- **Magnetic Fields Module:** Analyze field variation from embedded magnets  
- **Deformed Geometry Module:** Couple mechanical deformation with magnetic response  

### 3. Validation
Simulation outputs (force–displacement and magnetic variation plots) were validated against literature (Mohammadi et al., *Sci. Rep.*, 2021).

**Target sensitivities and ranges:**
| Layer | Sensitivity (N⁻¹) | Force Range (N) |
|:------|:------------------:|:---------------:|
| 1 | 0.26 | 0.9 |
| 2 | 0.08 | 4.8 |
| 3 | 0.03 | 16.2 |

---

## CAD Design

The metamaterial **unit cell** and **three-layer assembly** were modeled in SolidWorks and exported as STL files for fabrication and analysis.

- **Material:** Thermoplastic Polyurethane (TPU), Shore Hardness A85  
- **Design Parameters:**  
  - θ = (25°, 33°, 37°)  
  - t = (0.6, 1.0, 1.4) mm  
  - h = (2.0, 2.8, 3.5) mm  
--- 

## Repository Contents
- `docs/` → Project report and references  
- `cad_design/` → STL files and renders of the metamaterial design  
- `comsol_model/` → Multiphysics simulation model and results  

