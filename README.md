# Identifying high-impact consumers’ behavioural changes for flexibility and demand reduction in a net-zero energy system
This repository contains the scripts used to generate network files and the notebooks to reproduce figures in the main text and supplementary of the paper.
A preprint of the paper is available on arXiv: https://arxiv.org/abs/2508.04414

## Abstract


Achieving decarbonization across energy sectors requires demand-side transformation such as behavioural changes and end-use efficiency improvements to complement supply-side technological shifts. However, changing consumption patterns is challenging, and implementing efficiency measures requires time and investment, highlighting the need to prioritize strategies. We address this prioritization using a high-resolution model of the European energy system under net-zero emissions, assessing the system-wide impacts of reducing or shifting energy service demand across power, heating, transport, aviation, shipping, industry, and agriculture. Four stylised mechanisms (constant reduction, peak shaving, temporal shifting, and curtailment) that can be mapped to real-world phenomena are assessed for their impacts on system costs, electricity and heating prices, CO<sub>2</sub> price, and capacity needs. Results indicate that demand flexibility and curtailment yield the greatest benefits: shifting demand by 2 hours to align with solar output reduces system costs by 0.4\%, while curtailing 3.7\% of electricity demand during peak price periods cuts costs by 0.9\%.

## Repository Structure

- `notebooks` contains the Jupyter notebooks used for the evaluation of results.
- `scripts` and 'config files' can be used to generate the network files using pypsa-eur (https://github.com/PyPSA/pypsa-eur). The specific version of pypsa-eur that was used to implement the changes is also saved at ([https://github.com/Parisra/pypsa-eur/tree/merged](https://github.com/Parisra/pypsa-eur/tree/demand-management)).
Attention:
1. The scripts were used with pypsa-eur v0.11.0 and atlite v0.2.12. Adjustments to the code may be needed if later versions of pypsa-eur and atlite are used.
2. The notebooks is customised for networks of this study, so care should be taken
when using it to produce similiar figures for PyPSA network files.

## Access to files

All files necessary to reproduce the figures in the paper using the notebooks in this repository are available at: https://zenodo.org/records/TBD. 

