# MD-cloud-computing

Molecular Dynamics Simulation
## Overview

This repository demonstrates a **Molecular Dynamics (MD) simulation workflow** performed using **Google Colab**.

The project explores how a biomolecular structure behaves over time under simulated conditions. The workflow includes preparation of the molecular structure, energy minimization, equilibration, production simulation, and analysis of the resulting trajectory.

The project is intended as a computational biology learning project and demonstrates the use of computational tools for studying **protein structure and molecular dynamics**.

## Objectives

* Understand the basic principles of Molecular Dynamics simulation
* Prepare a protein structure for simulation
* Perform energy minimization and system equilibration
* Run a short MD simulation
* Analyze structural stability and molecular behavior
* Visualize simulation results and trajectories

## Workflow

```text
Protein Structure
       ↓
System Preparation
       ↓
Solvation & Ionization
       ↓
Energy Minimization
       ↓
Equilibration
       ↓
Production MD Simulation
       ↓
Trajectory Analysis
       ↓
Visualization & Interpretation
```

## Computational Environment

| Component                 | Tool                 |
| ------------------------- | -------------------- |
| Computational environment | Google Colab         |
| MD engine                 | GROMACS              |
| Programming / analysis    | Python               |
| Trajectory analysis       | MDAnalysis           |
| Molecular visualization   | UCSF Chimera / PyMOL |

## Analyses

The simulation trajectory is analyzed using measures such as:

* **RMSD (Root Mean Square Deviation)** — structural stability over time
* **RMSF (Root Mean Square Fluctuation)** — residue-level flexibility
* **Radius of Gyration (Rg)** — overall compactness of the protein
* **Hydrogen-bond analysis** — interactions maintained during simulation
* **Trajectory visualization** — structural changes throughout the simulation

## Google Colab

The complete workflow is implemented in a Google Colab notebook so that the simulation and analysis can be performed in a cloud-based computational environment without requiring a local MD installation.

**Notebook:** `MD_simulation_Colab.ipynb`

## Results

The resulting trajectories and analyses are used to examine the structural behavior and stability of the simulated protein.

Example outputs include:

* RMSD plot
* RMSF plot
* Radius of gyration plot
* Molecular structure/trajectory visualization

* # Molecular Dynamics Simulation

## Overview

This repository contains a computational Molecular Dynamics (MD) simulation workflow implemented in **Google Colab** to investigate the structural dynamics and stability of a protein system.

The workflow covers system preparation, energy minimization, equilibration, production MD, trajectory processing, and structural analysis.

## Computational Workflow

**Structure preparation → System setup → Energy minimization → NVT/NPT equilibration → Production MD → Trajectory analysis**

## Methods

The simulation workflow includes:

* Protein structure preparation and topology generation
* Solvation and addition of counterions
* Energy minimization
* NVT and NPT equilibration
* Production Molecular Dynamics
* Periodic boundary condition correction and trajectory processing
* Structural stability and flexibility analysis

### Trajectory Analysis

Structural dynamics are evaluated using:

* **RMSD** — assessment of global structural deviation
* **RMSF** — characterization of residue-level flexibility
* **Radius of gyration** — evaluation of structural compactness
* **Hydrogen-bond analysis** — characterization of persistent molecular interactions


## Results

The repository contains the processed simulation trajectory and quantitative analyses of structural deviation, residue flexibility, and molecular compactness.

Representative plots and molecular visualizations are provided in the `results/` directory.


## Scope

This project focuses on the computational implementation and analysis of an MD workflow. Biological interpretation is considered in the context of the simulated molecular system and the limitations imposed by simulation length, force-field selection, structural preparation, and sampling.

## Learning Outcomes

Through this project, I developed practical familiarity with:

* Molecular Dynamics simulation concepts
* Computational structural biology workflows
* Linux/command-line commands used in computational biology
* Running computational workflows in Google Colab
* Python-based trajectory analysis
* Interpretation of structural stability and flexibility metrics


## Author
# Amina Ayub
