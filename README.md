<p align="center">
    <img src="docs/qDNA_logo2.png" width="600">
</p>

# QuantumDNA Jupyter Notebook Tutorials

Welcome to the **QuantumDNA Jupyter Notebook Tutorials**! These tutorials are designed to help users explore and understand the functionalities of the `qDNA` package through practical examples.

## Overview

The tutorials are located in the [`tutorials`](tutorials) folder. Among them, the notebook [`PRE_2024`](tutorials/PRE_2024.ipynb) reproduces all the figures presented in the reference paper [1]. Additionally, the `tutorials` folder includes the following tutorials, covering various aspects of `qDNA`:

| **Tutorial Name**                                                                                  | **Description**                                                                                                                   |
|----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| [`1_Tight_Binding_Parameters`](tutorials/1_Tight_Binding_Parameters.ipynb)                         | Learn to use the Linear Combination of Atomic Orbitals (LCAO) approach with Slater–Koster two-center interaction integrals and Harrison-type expressions.   |
| [`2_Tight_Binding_Method`](tutorials/2_Tight_Binding_Method.ipynb)                                 | Explore predefined and custom tight-binding models. This tutorial demonstrates calculating time-averaged exciton populations in a Fishbone Ladder Model (FLM) and simulating charge transfer in the Fenna-Matthews-Olson (FMO) complex in green sulfur bacteria, showcasing how `qDNA` can define custom models. |
| [`3_Environment_Simulation`](tutorials/3_Environment_Simulation.ipynb)                            | Discover how to model DNA excited-state relaxation and environmental interactions using dephasing and thermalization models from Quantum Biology. |
| [`4_Visualization`](tutorials/4_Visualization.ipynb)                                              | Learn how to use predefined plotting routines for visualizing results effectively.                                       |
| [`5_Evaluation`](tutorials/5_Evaluation.ipynb)                                                    | Perform calculations for various observables, such as estimated exciton lifetimes, average charge separation, and dipole moments. This tutorial also demonstrates the use of parallelization capabilities. |
| [`6_Reproduce_Papers`](tutorials/6_Reproduce_Papers.ipynb)                                                    | This tutorial guides you through reproducing results from research papers [2-7] using the package. |

---

## Getting Started

These tutorials provide hands-on examples and explanations to help you effectively use the `qDNA` package. For each tutorial, navigate to the corresponding `.ipynb` file in the `tutorials` folder and follow the provided instructions.

---

## References

[1] [D. Herb, M. Rossini and J. Ankerhold, Ultrafast excitonic dynamics in DNA: Bridging correlated quantum dynamics and sequence dependence. *Physical Review E 109*, 064413 (2024).](https://doi.org/10.1103/PhysRevE.109.064413)

[2] [Mantela, Marilena and Lambropoulos, Konstantinos and Simserides, Constantinos, Charge transport properties of ideal and natural DNA segments, as mutation detectors. *Physical Chemistry Chemical Physics 25*, 7750--7762 (2023).](https://doi.org/10.1039/D3CP00268C)

[3] [Simserides, Constantinos, A systematic study of electron or hole transfer along DNA dimers, trimers and polymers. *Chemical Physics 440*, 31--41 (2014).](https://doi.org/10.1016/j.chemphys.2014.05.024)

[4] [Bittner, Eric R., Frenkel exciton model of ultrafast excited state dynamics in AT DNA double helices. *Journal of Photochemistry and Photobiology A: Chemistry 190*, 328--334 (2007).](https://doi.org/10.1016/j.jphotochem.2006.12.007)

[5] [Bittner, Eric R., Lattice theory of ultrafast excitonic and charge-transfer dynamics in DNA. *The Journal of Chemical Physics 125*, 094909 (2006).](https://doi.org/10.1063/1.2335452)

[6] [Giese, Bernd and Amaudrut, Jérôme and Köhler, Anne-Kathrin and Spormann, Martin and Wessely, Stephan, Direct observation of hole transfer through DNA by hopping between adenine bases and by tunnelling. *Nature 412*, 318--320 (2001).](https://doi.org/10.1038/35085542)

[7] [Giese, Bernd and Wessely, Stephan and Spormann, Martin and Lindemann, Ute and Meggers, Eric and Michel-Beyerle, Maria E., On the Mechanism of Long-Range Electron Transfer through DNA. *Angewandte Chemie International Edition 38*, 996--998 (1999).](https://doi.org/10.1002/(SICI)1521-3773(19990401)38:7<996::AID-ANIE996>3.0.CO;2-4)
