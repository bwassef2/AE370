# AE 370 Project 1 – Quadrotor Attitude Dynamics

## Overview

This repository contains the simulation and analysis for AE 370 Project 1, completed at the University of Illinois Urbana-Champaign. The project focuses on modeling the nonlinear rotational dynamics of a quadrotor and analyzing its behavior under various control and disturbance scenarios. The system is governed by Euler’s equations of motion and is numerically integrated using the fourth-order Runge-Kutta (RK4) method.

## Objective

The purpose of this project is to explore key aspects of quadrotor attitude dynamics, including system stability, control authority, parameter sensitivity, and response to external disturbances. These aspects are investigated through a series of controlled simulations that vary initial conditions, torque inputs, and system properties.

## Methodology

The rotational dynamics are modeled in Python and integrated using a custom implementation of the RK4 method. The system was verified through a convergence study, confirming the expected fourth-order accuracy of the numerical method. The codebase is modular, allowing for adjustments to time step, torque profiles, and inertia parameters to support multiple case studies.

## Results

Simulation results demonstrate the nonlinear and coupled nature of the attitude dynamics. Control inputs significantly affect system response, while changes in moment of inertia values lead to measurable variations in stability and performance. External disturbances, when applied, cause persistent changes in angular velocity in the absence of active control, illustrating the system’s sensitivity to real-world effects.

## Files

The repository includes a Jupyter notebook containing all code, simulations, and figures. The technical report, compiled from LaTeX, is provided as a PDF. All images from simulations can be found in `images`.

## Contributions

All group members contributed to modeling, coding, simulation design, and report writing. Work was divided among system definition, method implementation, results generation, and documentation.

## Reproducibility

The code can be run directly in Google Colab or any local Jupyter environment without additional setup. It uses standard Python libraries including NumPy and Matplotlib.

## Acknowledgments

ChatGPT was used during the development of this project to assist with code generation and debugging. All content was reviewed, tested, and finalized by the project team.
