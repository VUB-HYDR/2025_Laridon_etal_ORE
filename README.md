# SURFER pre3.0 with AMOC Tipping Calibration Module (ATCM)
---

__Paper :__ [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14979157.svg)](https://doi.org/10.12688/openreseurope.19479.1)

__Supplementary Material__ : [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14979157.svg)](https://doi.org/10.5281/zenodo.14979157)


<img width="4400" height="4000" alt="forcing_Space_T FGIS_v2" src="https://github.com/user-attachments/assets/ec35da1c-7957-4716-908e-b794f8382fe1" />



__This repository contains the SURFER pre3.0 models that integrates the AMOC Tipping Calibration Module (ATCM)__ used and described in Laridon et al.[1] _"Connecting Complex and Simplified Models of Tipping Elements: A Nonlinear Two-Forcing Emulator for the Atlantic Meridional Overturning Circulation"_

The ATCM is a tipping element emulator of the AMOC based on the normal form of a double-fold bifurcation. It is a two forcing variables system that allows to simulate the evolution of the AMOC under the temperature anomaly forcing and the freshwater flux forcing coming from the melting of the Greenland Ice Sheet. The ATCM can be calibrate based on three calibration experiments coming from a complex model. The calibration module is a generalization of the one present in Martinez Monteiro et al.[1,4]. 

SURFER is a reduced complexity climate model with a process-based carbon cycle [1,2]. We integrate the ATCM into SURFER pre3.0 to obtain a tipping element emulator of the AMOC integrate into a reduced complexity climate model.  



## ATCM
---

`ATCM.ipynb` is the Jupyter Notebook that contains the Python script of the AMOC Tipping Calibration Module. This notebook contains :

- Mathematical framework behind the AMOC Tipping Calibration Module (ATCM)
- The ATCM 
- The ATCM Calibration Validation test 
- cGENIE Emulation
    - Calibration of the internal dynamics parameters 
    - Calibration of the characteristic time scale parameter
- ATCM validation on other cGENIE experiments

### How to run

1. Change the `base_path` variable to the main directory in which you saved this repository.
2. Download the cGENIE simulations [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15021902.svg)](https://doi.org/10.5281/zenodo.15021902)
3. Upload the cGENIE simulations in the `base_path/data/cGENIE simulations/Paper simulations/` directory
4. Run the Notebook.


## SURFER pre3.0 with ATCM
---

`SURFER_pre3.0_ATCM.ipynb` is the Jupyter Notebook that contains the Python script of pre3.0 of SURFER climate model with the ATCM. 

### How to run 

1. Change the `base_path` variable to the main directory in which you saved this repository.
2. Run the Notebook.

## Version
---

Version August 2025

## cGENIE
---

The code for the version of the ‘muffin’ release of the cGENIE Earth system model used in this paper, is tagged as v0.9.61, and is assigned a DOI: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15021902.svg)](https://doi.org/10.5281/zenodo.15021902)

Configuration files for the specific experiments presented in the paper can be found in the directory: genie-userconfigs/PUBS/published/Laridon_et_al_2025. Details of the experiments, plus the command line needed to run each one, are given in the readme.txt file in that directory. All other configuration files and boundary conditions are provided as part of the code release.

A manual detailing code installation, basic model configuration, tutorials covering various aspects of model configuration, experimental design, and output, plus the processing of results, is assigned a DOI: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13377225.svg)](https://doi.org/10.5281/zenodo.13377225)






## Authors
---

__Amaury Laridon(1,2), Victor Couplet(2), Justin Gérard(2), Wim Thiery (1), Michel Crucifix(2)__

(1) Vrije Universiteit Brussel, Department of Water and Climate, bclimate Research Group, Brussels, Belgium.

(2) UCLouvain, Earth and Life Institute, Louvain-La-Neuve, Belgium.

Contact author : Amaury.Laridon@vub.be


## References
---

- [1] A. Laridon, V. Couplet, J. Gérard, W. Thiery, M. Crucifix, "Connecting Complex and Simplified Models of Tipping Elements: A Nonlinear Two-Forcing Emulator for the Atlantic Meridional Overturning Circulation", Open Research Europe, Jan. 2025, doi : ? 

- [2] M. Martínez Montero, M. Crucifix, V. Couplet, N. Brede, and N. Botta, ‘SURFER v2.0: a flexible and simple model linking anthropogenic CO2 emissions and solar radiation modification to ocean acidification and sea level rise’, Geoscientific Model Development, vol. 15, no. 21, pp. 8059–8084, Nov. 2022, doi: 10.5194/gmd-15-8059-2022.

- [3] V. Couplet, M. Montero, and M. Crucifix, SURFER v3.0: a fast model with ice sheet tipping points and carbon cycle feedbacks for short and long-term climate scenarios. 2024. doi: 10.5194/egusphere-2024-2279.

- [4] V. Couplet, N. Wunderling, and M. Crucifix, ‘Tipping interactions and cascades on multimillennial time scales in a model of reduced complexity’, 2024.


__This readme file was generated on [2025-08-18] by Amaury Laridon__

__Last updated: [2025-08-18].__



