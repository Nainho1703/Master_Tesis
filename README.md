# Master's Thesis: Study of the dynamics of Tuberculosis in urban and semi-urban environments in Argentina

## Overview

This repository contains the code and analysis for my Master's thesis, which focuses on modeling infection clusters and treatment outcomes for tuberculosis in Argentina, utilizing time series models (ARIMA, SARIMAX, LSTM) and evaluating treatment impacts based on socioeconomic variables and comorbidities.

## Repository Structure

### Folders

- **Additional**: Contains secondary code, used occasionally for data creation or extraction.
- **Bases**: Contains all datasets extracted, created, and modified for analysis.
- **Documentation**: Contains the figures and reports used in the project.
- **Models**: Stores the saved models for treatment outcome prediction.
- **Resultados**: Contains predictions from different models and random states.
- **utils**: Contains a file `utils.py` with all transversal functions.

### Files / Notebooks

1. **Cleaning.ipynb**: Code for data cleaning, including removal and modification of data.
2. **Analysis.ipynb**: Code for exploratory analysis.
3. **LISA.ipynb**: Code for clustering high/low incidence in each department.
4. **Modelling.ipynb**: Code for data imputation and model selection for treatment outcomes.
5. **Time_series.ipynb**: Code for time series model selection, including SARIMAX and LSTM.

## Evaluation Metrics

- **For Treatment Outcomes**: Accuracy, Precision, Log Loss.
- **For Time Series Models**: MAE, MSE, AIC, BIC.

## How to Clone This Repository

To clone this repository, use the following command in your terminal:

```bash
git clone https://github.com/Nainho1703/Master_Tesis.git
