# MARV Control System Linearization and Simulation

Course: EBB320 – Control Systems  
University of Pretoria  
Completed: September 2021  

---

## Project Overview

This project analysed the control system of the MARV line-tracking robot. The system consists of two motors and a sensor array used to follow coloured tracks.

The nonlinear dynamic model of the robot was linearized around an equilibrium point to allow easier analysis and control design. Transfer functions were derived from the resulting state-space model and simulations were performed to compare the behaviour of linear and nonlinear system models.

The simulations were implemented in Python to evaluate system behaviour under different control inputs and to analyse the accuracy of the linear approximation.

📄 **View full report:**  
[Project Report](docs/EBB320_Practical_Assignment_1.pdf)

The Python implementation used for the simulations is included in the appendix of the report.

---

## Objectives

- Model the nonlinear dynamics of the MARV robot
- Linearize the system around its equilibrium point
- Derive state-space matrices for the linear model
- Obtain transfer functions from the state-space representation
- Simulate both nonlinear and linear models
- Compare system responses under multiple control inputs
- Analyse how linearization affects model accuracy

---

## Tools & Technologies

- Python
- NumPy
- SciPy
- Matplotlib
- Differential equation simulation
- Control systems theory
- State-space modelling
- System linearization

---

## Notes

This repository contains the original academic report submitted for the EBB320 Control Systems course.

The Python code used for the system simulations and plots is included in the appendix of the report.
