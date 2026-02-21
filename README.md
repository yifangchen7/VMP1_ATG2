# Source code for the paper: *Molecular basis and function of scramblase VMP1 in complex with lipid transfer protein ATG2A*

This repository contains input files and analysis code used in the paper.

## Contents
### 1) Simulations
The `Simulation/` folder contains the input files required to run atomistic simulations with **GROMACS 2022.5**

Simulation trajectories are not included in this repository. For questions about accessing or using the trajectories, please contact:
- yc638@cam.ac.uk
- yongwang_isb@zju.edu.cn

### 2) Trajectory analysis
`Trajectory_analysis.ipynb` contains the analysis workflows used in the paper, including:
- POPC/water density analysis
- Protein–protein and protein–lipid (POPE) contact analysis
- Scrambled-lipid identification and counting
- Cavity volume approximation
- Tilt angle calculation

Some analyses require external tools:
- [GetContacts](https://getcontacts.github.io/)
- [Scramblyzer](https://github.com/Ladme/scramblyzer)
- [PLUMED](https://www.plumed.org/doc-v2.9/user-doc/html/index.html)
