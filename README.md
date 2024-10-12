# 2D Heat Conduction Problem - ANSYS Simulation

## Overview
This repository contains an ANSYS Workbench simulation for solving a steady-state 2D heat conduction problem with mixed boundary conditions. The simulation aims to determine the **dimensionless temperature distribution** and **heat flux** in a rectangular domain subjected to various thermal boundary conditions.

## Problem Description

**Geometry:** A rectangular domain with  width **𝑊** and height **𝐻=2𝑊**.

**Boundary Conditions:**
- **Bottom Wall:** Isothermal boundary **θ=1** (constant temperature).
- **Top and Left Walls:** Adiabatic boundary conditions **∂θ/∂y = 0** and  **∂𝜃/∂𝑥=0**   (no heat flux).
- **Right Wall:** Convective boundary condition **− ∂x/∂θ=Biθ**, with a Biot number **Bi=5**.

**Aspect Ratio:** **H/W**=2.

**Solver:** Steady-state thermal analysis in ANSYS Mechanical.

**Objective:** To compute the dimensionless temperature distribution and heat flux across the domain.

## Repository Structure
```plaintext
/
|-- results/           # Stores screenshots or plots of the results
|-- project_files/     # ANSYS project files (e.g., .wbpj, .agdb, etc.)
|-- docs/              # Documentation, screenshots, or relevant papers
|-- .gitignore         # Specifies which files to ignore in version control
|-- LICENSE            # License under which this project is distributed
|-- README.md          # This project overview and setup instructions
