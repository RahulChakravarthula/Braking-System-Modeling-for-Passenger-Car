# Passenger Car Braking System Simulation 🛑🚗

## Overview

A dynamic 1D simulation model of a passenger car braking system, developed in MATLAB/Simulink to analyze vehicle response under different braking torque inputs. This project demonstrates advanced model-based development skills and systematic performance evaluation methodologies applied to automotive braking dynamics.

## Project Scope
**Objective**: Simulate and evaluate vehicle deceleration, velocity reduction, and stopping distance under varying braking torque inputs.

**System Architecture**: Braking system simulation incorporating:
- Equations of motion for longitudinal vehicle dynamics
- Configurable braking torque input at the wheels
- Tire-road interaction modeled via rolling resistance and aerodynamic drag
- Outputs including velocity, displacement, and stopping distance

## Technical Implementation

### Simulation Framework
- **Platform**: MATLAB/Simulink
- **Model Type**: 1D dynamic vehicle braking model
- **Validation**: Physics-based equations of motion verified against standard vehicle dynamics formulations

### Key Components Modeled
1. **Vehicle Body Dynamics**: Mass, rolling resistance, aerodynamic drag
2. **Braking Torque Input**: Step, ramp, or variable braking torque applied
3. **Equations of Motion**: Integration of acceleration to compute velocity and displacement

### Analysis Methodology
- **Braking Scenarios**: Step braking torque, gradual ramp input, and variable profiles
- **Performance Metrics**: Deceleration curve, velocity profile, stopping distance

### Engineering Insights
- Direct correlation between applied braking torque and vehicle stopping distance.
- Tire-road interaction and wheel dynamics are critical for realistic braking behavior.
- Serves as a baseline for extending toward ABS (Anti-lock Braking System) or advanced stability control algorithms.

## Technical Stack

- **Simulation Environment**: MATLAB R2023a/Simulink
- **Modeling Approach**: Physics-based component modeling with empirical validation
- **Analysis Tools**: Sensitivity analysis framework with automated parameter sweeps
- **Visualization**: Comparative performance plots and comprehensive data tables

## Project Structure

```
├── ABS_Simulation.slx    # Main Simulink model
└── README.md             # Project documentation
```

## Applications

This model provides a foundation for:
- **Vehicle Dynamics Studies**: Fundamental braking performance analysis
- **Control System Development**: Basis for ABS/ESC algorithm design
- **Academic Research**: Teaching tool for automotive dynamics in MATLAB/Simulink
- **Industrial R&D**: Concept validation for braking and safety systems
