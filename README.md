# Turbulent Flow CFD Analysis in a Circular Pipe 🌊

## Project Overview
Numerical simulation of turbulent air flow in a pipe performed to validate the **k-omega SST turbulence model** against analytical solutions (Darcy-Weisbach equation).

**Key Results:**
- **CFD Pressure Drop:** 22,891 Pa
- **Analytical Pressure Drop:** 22,394 Pa
- **Relative Error:** **2.22%** ✅

## Tools Used
- **Software:** Ansys Fluent 2025 (Student Version)
- **Meshing:** Ansys Meshing (MultiZone method, Inflation layers)
- **Reporting:** LaTeX

## Methodology
- **Mesh:** Structured Hexa/Tetra hybrid mesh (~960k elements). Optimized for Student License limits.
- **Physics:** Compressible flow, k-omega SST model.
- **Validation:** Grid independence study performed. Boundary layer resolution confirmed with **y+ < 1** (max 0.68).

## Visualizations
![Velocity Profile](Images/contours_vel.png)
*Figure 1: Velocity magnitude distribution showing developed turbulent profile.*

![Mesh Quality](Images/mesh.png)
*Figure 2: Mesh cross-section with inflation layers.*

## Full Report
📄🇵🇱 [PL] [Download the full technical report in Polish (PDF)](Report/Raport_CFD_AGH_PL.pdf)
📄🇺🇸 [EN] [Download the full technical report in English (PDF)](Report/Report_CFD_AGH_EN.pdf)

