# 2D Heat Conduction Problem - ANSYS Simulation

## Overview

This repository contains an ANSYS Workbench simulation solving a steady-state 2D heat conduction problem with mixed boundary conditions. The simulation focuses on determining the **dimensionless temperature distribution** and **heat flux** in a rectangular domain subjected to different thermal boundary conditions.

## Problem Description

- **Geometry**: A rectangular domain with width \( W \) and height \( H = 2W \).
- **Boundary Conditions**:
  - Bottom wall: Isothermal boundary \( \theta = 1 \) (constant temperature).
  - Top and left walls: Adiabatic boundary \( \frac{\partial \theta}{\partial y} = 0 \) and \( \frac{\partial \theta}{\partial x} = 0 \), respectively (no heat flux).
  - Right wall: Convective boundary \( -\frac{\partial \theta}{\partial x} = \text{Bi} \theta \), with a **Biot number** \( \text{Bi} = 5 \).
- **Aspect Ratio**: \( H/W = 2 \).
- **Solver**: Steady-state thermal analysis in ANSYS Mechanical.
- **Objective**: To compute the dimensionless temperature distribution and heat flux.

## Repository Structure

```plaintext
/
|-- geometry/          # Contains CAD files (if any)
|-- meshes/            # Contains mesh files or settings
|-- results/           # Stores screenshots or plots of the results
|-- macros/            # Any ANSYS macros used for automation
|-- project_files/     # ANSYS project files (e.g., .wbpj, .agdb, etc.)
|-- docs/              # Documentation, screenshots, or relevant papers
|-- .gitignore         # Specifies which files to ignore in version control
|-- LICENSE            # License under which this project is distributed
|-- README.md          # This project overview and setup instructions
