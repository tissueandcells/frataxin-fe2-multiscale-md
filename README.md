# Multi-Scale MD Simulations of Fe2+ Coordination in Human Frataxin
fpocket blind prediction identifies Pocket 2 (HIS183-GLU184-ASP199) as a Fe2+ coordination site on human frataxin. Five independent methods confirm stable binding with dG = -33.50 kJ/mol, matching experimental Kd = 2-55 uM.

## Repository Contents

| Folder | Contents |
|--------|----------|
| 01_structure | PDB files, fpocket pocket atoms |
| 02_topology | GROMACS topology (apo, holo, control) |
| 03_mdp_parameters | All MDP files, PLUMED input |
| 04_analysis | RMSD, RMSF, RDF, PCA, DCCM, SASA, Rg, H-bonds, DSSP, clustering, MM energy, Fe2+ tracking |
| 05_extended | Force field comparison, metadynamics FES, tICA/MSM, QM/DFT (ORCA), alchemical FEP |

---

## Software

GROMACS 2023.2, CHARMM36m, PLUMED 2.9.2, ORCA 6.1.0, MDAnalysis 2.7.0, PyEMMA 2.5.12, ChimeraX 1.8

Total simulation time: ~2.7 microseconds (NVIDIA RTX 4060)

---

## Data Availability

Analysis files are in this repository. 

PDB: https://www.rcsb.org/structure/1EKG
