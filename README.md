# Modal Analysis of Two-Degree-of-Freedom Mass-Spring System | ME 351 - SP4

## 📌 Overview
This project involved analyzing a mechanical system consisting of two masses and three springs. The goal was to derive equations of motion, determine natural frequencies and mode shapes, and solve for time-dependent responses using modal analysis.

## ⚙️ System Description
- Two vertically moving masses (m₁ and m₂)
- Three linear springs with constants k₁, k₂, and k
- Three configurations analyzed: 
  - **Case A**: Symmetric masses and springs
  - **Case B**: Asymmetric masses
  - **Case C**: Stiff center spring

## 📐 Objectives
- Derive system equations using Newton’s Second Law
- Calculate natural frequencies and corresponding mode shapes
- Solve for displacement of each mass over time using initial conditions
- Compare system behavior across symmetric and asymmetric configurations

## 📊 Methodology
- Derived EOMs and converted to matrix form
- Solved characteristic equation for ω₁ and ω₂
- Applied initial condition: m₁ displaced 0.01 m, m₂ at rest
- Solved for displacement functions x₁(t) and x₂(t) in each case

## 🧪 Results Summary
| Case | ω₁ (rad/s) | ω₂ (rad/s) | Motion Pattern      |
|------|------------|------------|---------------------|
| A    | 30         | 10         | Symmetric In/Out of Phase |
| B    | 4.53       | 1.21       | Asymmetric amplitudes     |
| C    | 210        | 10         | High-frequency out-of-phase due to stiff center spring |

## 💡 Key Skills Applied
- Modal Analysis
- Linear Algebra & Differential Equations
- Matrix Method for Vibrations
- MATLAB & Manual Calculations
- Analytical System Modeling

## 📁 Files
- `SP4_Report.pdf`: Full writeup with equations, solutions, and plots
- `SP4_HandCalc.pdf`: Handwritten derivations and matrix algebra
- `SP4_MATLAB.m`: Code to compute and plot displacement solutions

## ✅ Assumptions
- Ideal spring/mass system (linear)
- No damping or external forces
- Constant system parameters
- Rigid masses, no deformation
