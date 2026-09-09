# BERN02_Exercise_Generalised-Linear-Models-on-Canvas
## Overview
This repository contains a Python implementation of a Poisson regression model designed to analyze and predict bird count trends over time. Using Maximum Likelihood Estimation (MLE), the model fits baseline counts and annual trend parameters, simulates Poisson realizations, and exports structured results to a CSV file.

## Mathematical Framework & Model Results
1. Model Formulation
   * Poisson distribution: $Y{i}$~$P$($\lambda{i}$)
   * Function link: $log$($\lambda{i}$) = $\beta_0$ + $\beta_1$ * $X{i}$
     
2. Maximum Likelihood Estimation
Parameters $\beta$ =($\beta_0$,$\beta_1)$ are estimated by Maximum likelihood estimation
via scipy.optimize.minimize:

3. Estimated Parameters
   $\beta_0$ = 2.3253
   $\beta_1$ = -0.0324
   
## How to Run
1. Ensure Python and required libraries (`numpy`, `css`, `matplotlib`, `scipy`) are installed.
2. Place `bird_count.csv` in the same directory as the script.
3. Output `bird_count_prediction.csv`.
4. Run the script:
   
```bash
python Bird_count.py
