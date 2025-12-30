# CAHS-Protein-Simulations
This repository contains molecular dynamics (MD) simulation setups, scripts, and analyses to investigate the assembly behavior of the CAHS12 protein and its interactions with a POPC lipid membrane using the Martini 3 coarse-grained force field. The simulations were designed to elucidate the mechanisms by which the CAHS12 protein protects lipid vesicles under dessication conditions. <br />

The following packages were used for running simulations and analyzing trajectories. The notebooks in each folder are used to analyze data and plot figures used in the paper.

`GROMACS 2022.4/2022.5`[GROMACS 2022 install guide](https://manual.gromacs.org/2022.4/install-guide/index.html)

`MDAnalysis 2.7.0`[Version installation page](https://www.mdanalysis.org/2024/01/04/release-2.7.0/)

`ChimeraX 1.9`[Download page](https://www.rbvi.ucsf.edu/chimerax/download.html)

## CAHS-dimer
This folder contains the .mdp, and .itp files for the five independent simulations of two CAHS12 proteins. The ie.mdp was used to rerun the trajectoeis and extract the short-range interaction energy between the proteins. The notebook pca.ipynb contains the codes for generating the PCA plots.  <br />

## CAHS-lipid
This folder contains the .mdp, and .itp files for setting up simulations of multiple CAHS12, CAHS12 ΔN, or CAHS12 ΔC proteins in the presence of a POPC membrane. Three independent simulations were carried out for each system. The notebooks, network.ipynb and quantification.ipynb, contain the codes for generating the network plots and statistics.   <br />

## water-deletion 
This folder contains the .mdp, and .itp files for running simulations to mimic the dehydration process for the CAHS12,CAHS12 ΔN, or CAHS12 ΔC system in the presence of a POPC membrane. The notebook water_depletion.ipynb plots the results extracted from the simulations with the .csv files.  <br />

## US_Dimer
This folder contains the .mdp, .itp files and plumed input for running US simulations of the dissociation processes of a CAHS12 dimer starting from a parallel and antiparallel conformations.  <br />

## POPC_POPG
This folder contains the .mdp, .itp files for running unbiased simulations of a single CAHS12 protein in the presence of a POPC membrane with different percentages of anionic POPG lipids. The notebook quantifies the residue contact frequency with the membrane and plots the results.  <br />

## Citation

If you find this useful, please cite: <br />

<pre> TBA


