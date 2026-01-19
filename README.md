# Cybership II Fuzzy-LQI Control Simulation

This repository contains the Python source code for the simulation results presented in the paper:

**"Adaptive Supervisory Control Strategy Integrating Fuzzy-LQR/LQI for Unmanned Surface Vehicles (USVs) under Varying Environmental Disturbances"**

## 1. Project Overview
This project simulates the path following control of the Cybership II USV model under two scenarios:
- **Scenario 1 (Summer):** Calm sea, nominal LQR control.
- **Scenario 2 (Winter):** Strong wind disturbances (4.0N), using Adaptive Fuzzy-LQI.

## 2. Requirements
To run the simulation, you need Python 3.x installed along with the following libraries:
- `numpy`
- `matplotlib`
- `scipy`

You can install them via pip:
```bash
pip install numpy matplotlib scipy
