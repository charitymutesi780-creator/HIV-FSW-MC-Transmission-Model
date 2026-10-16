# HIV-FSW-MC Transmission Model

This repository contains the R code and outputs for a deterministic compartmental HIV transmission model among female sex workers (FSWs) and male clients (MCs).
It also evaluates the impact of condoms, PrEP, and male circumcision on HIV transmission among female sex workers and male clients.
Model parameters, assumptions, and calibration targets are provided in the accompanying manuscript.

## Files

- HIV_Model.R : Main model code (Fifth_With_CM Rmd file)
- Outputs.xlsx : Model outputs (Fifth_With_CM HTML file)
- Sensitivity_Analysis.xlsx : Sensitivity analysis results

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
