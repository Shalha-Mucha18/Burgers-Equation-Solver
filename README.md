# Burgers' Equation Solver using Physics-Informed Neural Networks (PINN)
## Overview
This repository contains an implementation of solving Burgers' equation using Physics-Informed Neural Networks (PINN). PINNs are a class of neural networks that are trained to solve partial differential equations (PDEs) while satisfying the governing physics laws at the same time. In this project, we utilize PINNs to approximate solutions to Burgers' equation, a fundamental model in fluid dynamics and nonlinear wave propagation.
## Features
- Implementation of Burgers' equation solver using PINNs in TensorFlow.
- Training and evaluation scripts for solving the equation in both 1D and 2D domains.
- Visualization tools for plotting the learned solutions and comparing with analytical or numerical solutions.
- Modular code structure for easy experimentation with different network architectures, loss functions, and training hyperparameters.
## Requirements
- Python 3
- TensorFlow 2
- NumPy
- Matplotlib
## Dataset
The dataset generation is handled within the code using techniques such as random sampling or grid discretization depending on the problem dimensionality.
