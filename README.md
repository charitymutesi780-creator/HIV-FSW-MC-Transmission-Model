# HIV-FSW-MC Transmission Model

This repository contains the R code and outputs for a deterministic compartmental HIV transmission model among female sex workers (FSWs) and male clients (MCs).
It also evaluates the impact of condoms, PrEP, and male circumcision on HIV transmission among female sex workers and male clients.
Model parameters, assumptions, and calibration targets are provided in the accompanying manuscript.

## Files

- HIV_Model.R : Main model code
- Outputs.xlsx : Model outputs
- Sensitivity_Analysis.xlsx : Sensitivity analysis results
- Heatmap.png : Heat map showing HIV prevalence under varying intervention coverages

## Requirements

R version 4.4 or later

Required packages:
- deSolve
- ggplot2
- reshape2
- dplyr

## Reproducing Results

1. Open HIV_Model.R in RStudio.
2. Install required packages.
3. Run the script from start to finish.
4. Outputs will be generated automatically.
