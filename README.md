# Riverine chemistry for the MARTINI project

This repository contains code for estimating riverine inputs to Skagerrak from major rivers in Norway, Sweden and Denmark. These datasets are required to support marine modelling undertaken as part of the MARTINI project.

## Data processing notebooks

 1. **[Data pre-processing](http://nbviewer.jupyter.org/github/JamesSample/martini/blob/master/notebooks/water_chem.ipynb)**. Standardising raw data from Norway, Sweden and Denmark
 
 2. **[Estimating daily concentrations](http://nbviewer.jupyter.org/github/JamesSample/martini/blob/master/notebooks/process_norway_chem.ipynb)**. Developing regression relationships to estimate daily concentrations for as many stations as possible
 
## Plots and visualisations

 * **[Raw data time series](https://github.com/JamesSample/martini/tree/master/plots/raw_data)**. Simple grid plots of the raw data
 
 * **[Concentration-discharge regressions](https://github.com/JamesSample/martini/tree/master/plots/flow_conc_reg)**. Fitted regression models of log(C) versus log(Q) for each parameter at each site
  
 * **[Simulated daily time series](https://github.com/JamesSample/martini/tree/master/plots/daily_series)**. Estimated time series of daily water chemistry for each location

## Output datasets

Results files in CSV format are available **[here](https://github.com/JamesSample/martini/tree/master/data/tidy)**.
