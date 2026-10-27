# Aerodynamics and Aircraft Design

A three-stage project completed for **AE 244** at IIT Bombay, exploring airfoil aerodynamics, computational lifting-line theory, and preliminary aircraft configuration design. The work combines analytical methods, Python programming, and simulation tools to study aerodynamic performance from a 2D airfoil to a complete glider concept.

## Project stages

### Stage 1 — Airfoil Analysis
**File:** `Report_Part1.pdf`

Created a NACA airfoil CAD model and mesh, then simulated the flow in **ANSYS Fluent** under different angles of attack. The report examines lift, drag, and pitching-moment trends, alongside streamline, velocity, pressure, pressure-coefficient, and vorticity plots. Key outputs include a maximum lift coefficient of approximately **1.34**, stall near **16°**, and a maximum \(C_L/C_D\) of **41.36**.

### Stage 2 — Python Lifting-Line / Airfoil Flow Model
**File:** `Report_Part2.pdf`

Developed a Python model for a NACA airfoil using the camber-line geometry and slope, Fourier coefficients, and circulation distribution. The implementation calculates lift coefficient, estimates the velocity field using induced-velocity relationships, and evaluates total circulation through numerical integration. Results are compared with ANSYS simulations, highlighting agreement in the lift curve before stall and the effect of neglecting viscosity in the Python model.

### Stage 3 — Preliminary Aircraft and Glider Design
**File:** `Report_Part3.pdf`

Extended the aerodynamic study to a finite wing and aircraft configuration. The report covers wing design and comparison of **Lifting-Line Theory** with **OpenVSP**, as well as fuselage, horizontal-stabiliser, and vertical-stabiliser modelling. It then brings these components together in a glider concept and estimates aerodynamic performance, weight, and optimum glide angle.

## Repository structure

```text
.
├── Airfoil_Code.py
├── README.md
├── Report_Part1.pdf
├── Report_Part2.pdf
└── Report_Part3.pdf
```

- **`Airfoil_Code.py`** — Python source file for the airfoil-related calculations.
- **`Report_Part1.pdf`** — Airfoil geometry, meshing, and ANSYS flow analysis.
- **`Report_Part2.pdf`** — Python-based camber-line, circulation, and velocity-field calculations.
- **`Report_Part3.pdf`** — Wing, fuselage, stabiliser, and glider design studies.

## Tools and methods

- **Python** — numerical calculations and visualisation.
- **NumPy / Matplotlib** — array-based computation and plots.
- **ANSYS Fluent** — viscous flow simulation around the airfoil.
- **OpenVSP** — aerodynamic analysis and aircraft configuration modelling.
- **Lifting-Line Theory** — finite-wing lift estimation and comparison with simulation.

## Notes

This repository contains academic coursework and preliminary design analyses. Some simulation results in the reports are identified as inaccurate or inconsistent and should be treated accordingly; they are not validated aircraft-performance predictions.

## Author

**Anuttar Jain**  
Department of Aerospace Engineering, IIT Bombay
