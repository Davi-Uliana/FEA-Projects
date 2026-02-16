
# Finite Element Analysis of an Aluminium Gearbox (ANSYS)

## Project Overview
This project presents a comprehensive finite element analysis (FEA) of an aluminium gearbox
subjected to combined thermal and mechanical loading. The work was completed as part of the
*MSc in Numerical Simulation in Engineering* and focuses on applying robust modelling,
verification and interpretation practices using ANSYS Workbench.

The analysis chain includes:
- Thermal–structural coupling
- Modal and harmonic response
- Linear buckling
- Non-linear elastoplastic behaviour
- Sub-modelling of critical stress regions

## Objectives
- Assess structural integrity under combined thermal and mechanical loads
- Identify stress concentrations and evaluate their physical relevance
- Determine dynamic characteristics and resonance behaviour
- Evaluate buckling stability margins
- Apply sub-modelling techniques to refine local stress predictions

## Boundary Conditions
<img width="3838" height="1533" alt="BCs" src="https://github.com/user-attachments/assets/399a7ca1-a71c-4b15-b85b-baeed238ecbe" />

## Tools & Methods
- Software: ANSYS Workbench (Mechanical)
- Element types: 3D solid elements
- Material model: Aluminium alloy (linear elastic and bilinear isotropic hardening)
- Analysis types:
  - Steady-state thermal
  - Static structural
  - Modal analysis
  - Harmonic response
  - Linear buckling
  - Non-linear static
  - Sub-modelling with cut-boundary verification

## Key Engineering Considerations
- Mesh convergence and element quality assessment
- Comparison of averaged vs unaveraged stresses
- Identification of stress singularities at geometric discontinuities
- Verification of sub-model boundary conditions using linearised stress
- Interpretation of non-linear convergence behaviour

## Results Summary
- High safety factors across most of the structure, with local stress concentrations near support holes
- Resonant frequency identified at approximately 1050 Hz with dominant response along the X-axis
- Buckling analysis indicating a safety factor greater than 100 for applied internal pressure
- Sub-modelling reduced peak stress from ~281 MPa (full model) to ~230 MPa after geometric refinement

## Repository Structure
- `overview/` – geometry and workflow overview
- `model-setup/` – boundary conditions, loads, assumptions
- `mesh-convergence/` – mesh refinement and quality checks
- `results/` – thermal, dynamic, buckling and non-linear results
- `submodel/` – cut-boundary verification and refined stress results
- `animations/` – dynamic and buckling visualisations
- `report/` – full academic report (PDF)

## Notes
This repository is intended to showcase engineering judgement and modelling practices rather
than act as a full academic submission. The complete report is included for reference.

## LInear Analysis Cases and Loads

<img width="1731" height="551" alt="image" src="https://github.com/user-attachments/assets/224f4d80-fe25-419d-b317-fdfe790563fc" />


