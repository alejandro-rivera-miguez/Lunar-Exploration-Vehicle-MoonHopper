# Lunar Exploration Vehicle: MoonHopper 🌕🚀

[![Domain](https://img.shields.io/badge/Domain-Space_Systems_Design-blue.svg)]()
[![Type](https://img.shields.io/badge/Type-Conceptual_Design-orange.svg)]()
[![Universidad de Sevilla](https://img.shields.io/badge/Academic-Universidad_de_Sevilla-red?style=flat-square&logo=university&logoColor=white)](https://www.us.es/)

A comprehensive conceptual and preliminary design of the **MoonHopper**, a lunar exploration vehicle capable of executing suborbital ballistic jumps to traverse challenging terrain. 

Developed by the fictional aerospace company *LunarXplorer* as the capstone project for the **Aerospace Engineering Projects (Proyectos de Ingeniería Aeroespacial)** course during the 4th year of the Bachelor's Degree at Universidad de Sevilla (2022-2023).

---

## 📌 Project Overview

Traditional lunar rovers face severe mobility limitations when exploring rugged environments like the lunar South Pole. The **MoonHopper** overcomes these obstacles by utilizing a propulsive hopping mechanism, enabling it to perform ballistic jumps between 0.5 km and 5 km, carry up to 180 kg of payload, and perform hovering maneuvers.

This project covers the full multidisciplinary design of the vehicle, from mission architecture and trajectory analysis to the sizing of all critical onboard subsystems.

### 🎯 Core Engineering Modules

#### 1. Mission Planning & Environment
* **Lunar South Pole Exploration:** Site selection targeting the Shackleton crater and surrounding regions (Haworth, Shoemaker) for potential water-ice extraction.
* **Environmental Analysis:** Accounting for lunar gravity, extreme thermal gradients, and lack of atmosphere.

#### 2. Trajectory & Locomotion Analysis
* **Ballistic Jumps:** Kinematic and dynamic modeling of the hopping trajectories.
* **Flight Profile:** Optimization of ascent, ballistic coast, and powered descent phases, including a mandatory 20-second hovering capability.

#### 3. Propulsion System
* Selection and sizing of the main and attitude control thrusters.
* Propellant budget calculations to meet the strict maximum acceleration limit (2g) and total mission $\Delta V$ requirements.

#### 4. Structures & Design
* **CAD Layout:** 3D conceptual modeling of the vehicle.
* **Anti-Rollover Mechanism:** Design of passive and active structural systems to ensure a safe landing and upright orientation on uneven lunar terrain.
* **Mass & Inertia Budget:** Detailed weight breakdown of all subsystems.

#### 5. Avionics, Power & Communications
* **Power System:** Sizing of primary and secondary batteries to ensure autonomous operation without heavy reliance on constant solar exposure in shadowed craters.
* **Telecom & Data Handling:** Link budget calculations for lunar-Earth communications and internal data bus architecture.
* **Navigation (GNC):** Sensor suite selection (IMUs, star trackers) and flight control computer architecture for autonomous hopping execution.

## 📂 Repository Contents

* **`docs/`**: Contains the exhaustive final project report (150+ pages), the executive presentation, and backup technical slides with detailed mission planning data and telemetry budgets.

## 👨‍💻 Authors (LunarXplorer Company)

* **Alejandro Rivera Míguez**
* *(Group 3 Team Members)*

---

Professor: **Eduardo Jose Sanz de Lucas**  
Master in Aeronautical Engineering | Universidad de Sevilla

---
*Disclaimer: This is an academic capstone project. The conceptual models and subsystem sizing data provided are intended for educational demonstration of space systems engineering.*
