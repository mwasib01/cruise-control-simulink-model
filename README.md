# Cruise Control System Modelling and Simulation

MATLAB/Simulink based cruise control system developed to model vehicle longitudinal dynamics and analyse controller performance under different driving conditions.

The project focuses on designing and evaluating a cruise control system that maintains the desired vehicle speed by adjusting the applied driving force while considering vehicle mass, aerodynamic resistance, rolling resistance, and road conditions.

## Project Overview

The model consists of:

- Vehicle longitudinal dynamics model
- Cruise control feedback system
- Speed error calculation
- Controller design
- Throttle/force adjustment mechanism
- Simulation-based performance evaluation

The controller continuously compares the reference speed with the actual vehicle speed and adjusts the control input to minimise the speed tracking error.


---

## Model Features

- Vehicle longitudinal dynamics simulation
- Closed-loop speed control
- Feedback-based error correction
- Vehicle speed tracking analysis
- Controller response evaluation
- MATLAB/Simulink implementation

---

## System Architecture

The cruise control system follows a closed-loop control structure:

1. Desired speed is provided as the reference input.
2. Vehicle speed is measured through feedback.
3. Speed error is calculated.
4. Controller generates the required control action.
5. Vehicle dynamics respond to the applied force.
6. Feedback updates the controller response.

---

## Simulation Analysis

The model was evaluated using MATLAB/Simulink simulations.

The analysis includes:

- Vehicle speed response
- Reference speed tracking
- Controller behaviour
- Control input variation
- Error response during operation

---

## Results

Simulation outputs demonstrate the response of the cruise control system under different operating conditions.

Key evaluated parameters:

- Vehicle velocity
- Reference velocity
- Tracking error
- Controller output
- Applied driving force

Selected simulation figures are available in the `figures` directory.

---

## Software Used

- MATLAB
- Simulink
- Control System Toolbox

---

## Project Applications

This model represents the fundamental control architecture used in automotive driver assistance systems, including:

- Cruise control systems
- Vehicle speed regulation
- Longitudinal vehicle control
- Automotive control development

---

## Author

Muhammad Wasib

MSc Automotive Engineering  
Birmingham City University


