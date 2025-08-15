# Morris–Lecar Parameter Estimation

This project investigates parameter estimation in the Morris–Lecar neuronal excitability model using two approaches:
- Maximum Likelihood Estimation (MLE)
- Parameter Cascade Method with Functional Data Analysis (pCODE in R)

## Project Overview
- Simulated noisy membrane voltage (`v`) and recovery variable (`w`) trajectories
- Applied both MLE and pCODE methods to recover key biophysical parameters (`gca`, `phi`)
- Compared accuracy and robustness under varying Gaussian noise conditions

## Tools & Packages
- R (`deSolve`, `pcode`, `fda`, `ggplot2`)
- B-spline smoothing
- Simulation & statistical optimization

## Results
- pCODE method reduced parameter estimate variability by >50% compared to MLE under high noise
- Provided improved robustness and reproducibility in noisy biological datasets

## Files
- `morris_lecar_code.R` – R scripts for simulation and estimation
- `project_report.pdf` – Full project report
- `results/` – Key figures and visualizations

## Author
Gefei Zhang – BSc Biology & Mathematics, McGill University
