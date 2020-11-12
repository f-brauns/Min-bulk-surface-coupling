This repository provides the code associated with the paper:

# Bulk-surface coupling reconciles Min-protein pattern formation in vitro and in vivo 

**Authors: Fridtjof Brauns, Grzegorz Pawlik, Jacob Halatek, Jacob Kerssemakers, Erwin Frey, Cees Dekker**

Preprint: https://www.biorxiv.org/content/10.1101/2020.03.01.971952


## Linear stability analysis

Linear stability analysis, as described in the Supplementary Information of the paper, was implemented in Mathematica. Details on the implementation are described in the Mathematica notebook Mathematica/linear-stability-analysis.nb.

## Numerical simulations

Numerical simulations were performed in COMSOL Multiphysics. Template setup files for the simulation setup in 1+2d geometry and 2+3d geometry (as described in the Supplementary Information of the paper) are provied in the respective .mph files in the directory "COMSOL Setup/". 

The Mathematica code used to analyze the patterns found in numerical simulations is provided in the notebook: "Mathmatica/front-width_Dc-sweep.nb", which loads exported simulation data from the directory "Mathematica/Dc-sweep_COMSOL-data/". Specifically, this code determines the front widths of standing wave patterns and compares them to the prediction from linear stability analysis as a function of the cytosolic diffusion constant Dc. Details are provided in the Supplementary Information of the paper.
