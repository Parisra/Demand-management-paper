# Pathways to Net-Zero: Exploring consumer’s behavioral changes for flexibility and demand reduction from a system perspective
This repository contains the scripts used to generate network files and the notebooks to reproduce figures in the main text and supplementary of the paper.


## Abstract


Managing energy demand has long been the most straightforward scheme for reducing the burden on the energy system. As we push for deep decarbonization across energy sectors, transitioning demand alongside supply becomes even more important, and in some cases, necessary. However, changing citizen consumption patterns is challenging, and implementing efficiency measures requires time and investment, necessitating the need to prioritize strategies. This study investigates which sectors offer the most benefits when their demand is reduced or reshaped, from a European macro-energy system point of view. The model integrates power, heating, land transport, industry, agriculture, aviation, and shipping. We analyze different static and dynamic demand reduction strategies including constant reduction, peak demand curtailment, flexible demand shifting, and penalized demand curtailment, for a net-zero scenario in 2050. Our results show that demand flexibility and curtailing energy use during periods of low renewable generation are the most cost-effective solutions. Sectors that rely heavily on oil and gas have the biggest impact on lowering carbon prices, while consumers can save the most by reducing electricity use during peak hours.


## Repository Structure

- `notebooks` contains the Jupyter notebooks used for the evaluation of results.
- `scripts` and 'config files' can be used to generate the network files using pypsa-eur (https://github.com/PyPSA/pypsa-eur). The specific version of pypsa-eur that was used to implement the changes is also saved at ([https://github.com/Parisra/pypsa-eur/tree/merged](https://github.com/Parisra/pypsa-eur/tree/demand-management)).
Attention:
1. The scripts were used with pypsa-eur v0.11.0 and atlite v0.2.12. Adjustments to the code may be needed if later versions of pypsa-eur and atlite are used.
2. The notebooks is customised for networks of this study, so care should be taken
when using it to produce similiar figures for PyPSA network files.

## Access to files

All files necessary to reproduce the figures in the paper unsing the notebooks in this repository are available at: https://zenodo.org/records/TBD. 

