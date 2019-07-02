# Riverine chemistry for the MARTINI project

This repository contains code for exploring and processing water chemistry data for major rivers draining to Skagerrak. These datasets are required to support marine modelling undertaken as part of the MARTINI project.

The analysis presented here considers 39 rivers: 25 in Norway, 5 in Sweden and 9 in Denmark (see [here](https://github.com/JamesSample/martini/blob/master/tidied_data_series/martini_river_outlets.xlsx) for a complete list). The links below provide full details of the work so far.

## Data processing notebooks

 * **[Initial data exploration](http://nbviewer.jupyter.org/github/JamesSample/martini/blob/master/notebooks/water_chem.ipynb)**. Exploring available river chemistry datasets and various methods for standardising and resampling the raw data
 
 * **[Water chemistry for Norwegian rivers](http://nbviewer.jupyter.org/github/JamesSample/martini/blob/master/notebooks/process_norway_chem.ipynb)**. Estimating daily water chemistry time series for the 25 Norwegian sites

 * **[Water chemistry for Swedish rivers](http://nbviewer.jupyter.org/github/JamesSample/martini/blob/master/notebooks/process_sweden_chem.ipynb)**. Estimating daily water chemistry time series for the 5 Swedish sites
 
## Plots and visualisations

 * **[Raw data time series](https://github.com/JamesSample/martini/tree/master/plots/raw_data)**. Simple grid plots of the raw data
 
 * **[Concentration-discharge regressions](https://github.com/JamesSample/martini/tree/master/plots/flow_conc_reg)**. Fitting linear regression models of log(C) versus log(Q) for each parameter at each site
 
 * **[Regression residuals](https://github.com/JamesSample/martini/tree/master/plots/flow_conc_reg_resid)**. Simple diagnostic plots for the fitted regressions
 
 * **[Simulated daily time series](https://github.com/JamesSample/martini/tree/master/plots/daily_series)**. Estimated time series of daily water chemistry for each location

## Output datasets

CSV files of estimated daily water chemistry (and flow, for some locations) are available [here](https://github.com/JamesSample/martini/tree/master/tidied_data_series).
