# Kartik Suresh Tandel

**Computational Mechanics | Computational Materials Science | Finite Element Analysis | Scientific Python**

M.Sc. Computational Materials Science — **TU Bergakademie Freiberg**

I develop numerical models for problems in **material behavior, solidification and structural mechanics**. My interests include deriving finite-element formulations, implementing numerical solvers in Python, and interpreting simulation results through physical and numerical checks.

My repositories document the underlying equations, computational approach, selected results, and the current scope of numerical verification.

## Featured computational engineering projects

### 01 · Phase-field modeling of dendritic solidification

**[FEniCSx Implementation of a Two-Dimensional, Thermally Coupled Phase-Field Model for Dendrite Growth](https://github.com/KartikTandel30/fenicsx-thermally-coupled-dendrite-growth)**

Development of phase-field simulations for solid–liquid interface evolution using **FEniCSx / DOLFINx**. The work explores mixed finite elements, implicit time integration, Newton solvers, thermal diffusion and four-fold interfacial anisotropy. The repository distinguishes coupled-model development from the currently showcased anisotropy-focused benchmark.

**Numerical methods:** FEniCSx · UFL · PETSc · MPI · Backward Euler · Nonlinear FEM

[![Phase-field morphology from the dendrite-growth project](https://raw.githubusercontent.com/KartikTandel30/fenicsx-thermally-coupled-dendrite-growth/main/Task_3/outputs/2/t300.png)](https://github.com/KartikTandel30/fenicsx-thermally-coupled-dendrite-growth)

### 02 · Nonlinear finite element analysis of a viscoplastic bar

**[Nonlinear FEM Viscoplasticity](https://github.com/KartikTandel30/nonlinear-fem-viscoplasticity)**

A Python implementation of incremental **one-dimensional nonlinear FEM** for a stepped bar with rate-dependent viscoplastic behavior. The project covers constitutive updates, numerical integration, element stiffness and internal forces, global assembly and Newton–Raphson equilibrium iterations.

**Numerical methods:** Python · NumPy · Constitutive Modeling · Newton–Raphson · Gauss Quadrature

### 03 · Structural finite element modal analysis

**[Structural FEM Modal Analysis](https://github.com/KartikTandel30/structural-fem-modal-analysis)**

A Python-based exploration of **free-vibration analysis** for a two-dimensional bridge-like structure. Geometry and material inputs are read from CSV files and the workflow covers element assembly, boundary conditions, generalized eigenvalue analysis and mode-shape visualization. The repository documents the limitations of its current simplified element formulation.

**Numerical methods:** Python · NumPy · SciPy · Quadrilateral Elements · Generalized Eigenvalue Problems

## Technical focus

| Area | Methods and tools used in my projects |
|---|---|
| **Computational mechanics** | Finite element methods, weak formulations, element assembly, boundary conditions |
| **Nonlinear numerical analysis** | Newton–Raphson iterations, tangent stiffness, incremental and implicit time integration |
| **Materials modeling** | Phase-field methods, interfacial anisotropy, diffusion, rate-dependent viscoplasticity |
| **Structural dynamics** | Stiffness/mass matrices, eigenvalue problems, vibration mode shapes |
| **Scientific software** | Python, NumPy, SciPy, pandas, Matplotlib, FEniCSx/DOLFINx, UFL, PETSc, MPI |

## Engineering approach

**Physical model → mathematical formulation → finite-element discretization → numerical solution → post-processing → verification**

The repositories contain source code, computational methodology and supporting results. They also identify verification work that remains outstanding; illustrative figures are not presented as independent numerical validation.

---

**Explore my work:** [Repositories](https://github.com/KartikTandel30?tab=repositories) · [Dendrite Growth](https://github.com/KartikTandel30/fenicsx-thermally-coupled-dendrite-growth) · [Viscoplastic FEM](https://github.com/KartikTandel30/nonlinear-fem-viscoplasticity) · [Modal Analysis](https://github.com/KartikTandel30/structural-fem-modal-analysis)
