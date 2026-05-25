# 2-Axis Gantry Robot Control Simulation (MATLAB/Simulink)

This repository contains a MATLAB/Simulink simulation of a **2-axis gantry robot** driven by two **Induction Motors (IM)**. Each axis is precisely controlled using **Indirect Rotor Flux Oriented Control (IRFO)** to achieve high-performance trajectory tracking. 

As a proof of concept, the control system successfully drives the robot to trace a precise **circular trajectory**.

## 💡 Key Features
* **2-Axis Gantry Modeling:** Kinematic and dynamic modeling of the robot structure.
* **Induction Motor Drive:** Power electronics and machine modeling for both axes.
* **IRFO Control (Vector Control):** Implementation of Indirect Rotor Flux Oriented Control for decoupled flux and torque regulation.
* **Trajectory Tracking:** Circular interpolation and path tracking validation.

## 🛠️ Tech Stack
* **Software:** MATLAB / Simulink
* **Toolboxes Used:** Simscape Electrical (or Power Systems), Control System Toolbox

## 📊 Results
The final simulation demonstrates excellent dynamic response and decoupling. The X and Y axes synchronize accurately to draw a circle, proving the effectiveness of the IRFO command under trajectory constraints.
