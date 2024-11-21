# QuantumDNA Jupyter Notebook Tutorials

Welcome to the **QuantumDNA Jupyter Notebook Tutorials**! These tutorials and demonstrations are designed to help users explore and understand the functionalities of the `qDNA` package through practical examples.

## Overview

The tutorials are located in the [`tutorials`](docs/tutorials) folder. Among them, the notebook [`PRE_2024`](tutorials/PRE2024.ipynb) reproduces all the figures presented in the reference paper [1].

Additionally, the `tutorials` folder includes the following tutorials, covering various aspects of `qDNA`:

| **Tutorial Name**                                                                                  | **Description**                                                                                                                   |
|----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| [`1_Tight_Binding_Parameters`](tutorials/1_Tight_Binding_Parameters.ipynb)                         | Learn to use the Linear Combination of Atomic Orbitals (LCAO) approach with Slater–Koster two-center interaction integrals and Harrison-type expressions.   |
| [`2_Tight_Binding_Method`](tutorials/2_Tight_Binding_Method.ipynb)                                 | Explore predefined and custom tight-binding models. This tutorial demonstrates calculating time-averaged exciton populations in a Fishbone Ladder Model (FLM) and simulating charge transfer in the Fenna-Matthews-Olson (FMO) complex in green sulfur bacteria, showcasing how `qDNA` can define custom models. |
| [`3_Environment_Simulation`](tutorials/3_Environment_Simulation.ipynb)                            | Discover how to model DNA excited-state relaxation and environmental interactions using dephasing and thermalization models from Quantum Biology. |
| [`4_Visualization`](tutorials/4_Visualization.ipynb)                                              | Learn how to use `qDNA`'s predefined plotting routines for visualizing results effectively.                                       |
| [`5_Evaluation`](tutorials/5_Evaluation.ipynb)                                                    | Perform calculations for various observables, such as estimated exciton lifetimes, average charge separation, and dipole moments. This tutorial also demonstrates the use of `qDNA`'s parallelization capabilities. |

---

## Getting Started

These tutorials provide hands-on examples and explanations to help you effectively use the `qDNA` package. For each tutorial, navigate to the corresponding `.ipynb` file in the `tutorials` folder and follow the provided instructions.

---

## References

[1] [D. Herb, M. Rossini and J. Ankerhold, Ultrafast excitonic dynamics in DNA: Bridging correlated quantum dynamics and sequence dependence. *Physical Review E 109*, 064413 (2024).](https://doi.org/10.1103/PhysRevE.109.064413)
