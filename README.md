# MD-cloud-computing
# Molecular Dynamics Simulation

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

## Tools & Technologies

Computational Environment
Component	Tool
Computational environment	Google Colab
MD engine	GROMACS
Programming / analysis	Python
Trajectory analysis	MDAnalysis
Molecular visualization	UCSF Chimera / PyMOL
Interactive workflow / Jupyter Notebook 

## Analyses

The simulation trajectory is analyzed using measures such as:

* **RMSD (Root Mean Square Deviation)** — structural stability over time
* **RMSF (Root Mean Square Fluctuation)** — residue-level flexibility
* **Radius of Gyration (Rg)** — overall compactness of the protein
* **Hydrogen-bond analysis** — interactions maintained during simulation
* **Trajectory visualization** — structural changes throughout the simulation

## Repository Structure

```text
MD-Simulation/
│
├── README.md
├── notebooks/
│   └── MD_simulation_Colab.ipynb
│
├── input/
│   └── protein.pdb
│
├── analysis/
│   ├── RMSD/
│   ├── RMSF/
│   └── Radius_of_Gyration/
│
├── results/
│   ├── figures/
│   └── processed_data/
│
└── images/
    └── workflow.png
```

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

## Learning Outcomes

Through this project, I developed practical familiarity with:

* Molecular Dynamics simulation concepts
* Computational structural biology workflows
* Linux/command-line commands used in computational biology
* Running computational workflows in Google Colab
* Python-based trajectory analysis
* Interpretation of structural stability and flexibility metrics


## Author

Amina Ayub

Exploring Bioinformatics & Computational Biology
