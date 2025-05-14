# Bayesian Inference for Survival Analysis

This repository contains a Bayesian analysis of survival proxies using PyMC and Python. The project analyzes physiological data to understand factors affecting survival outcomes.

## Project Structure

- `physionet.org/files/crisdb/1.0.0/BayesianInference.ipynb`: Main Jupyter notebook containing the Bayesian analysis
- `physionet.org/files/crisdb/1.0.0/patient_data.pkl`: Processed patient data used in the analysis
- `physionet.org/files/rr_e/`: RR interval data for exercise condition
- `physionet.org/files/rr_m/`: RR interval data for meditation condition
- `physionet.org/files/rr_f/`: RR interval data for relaxation condition

## Features

- Bayesian modeling of the relationship between physiological parameters and survival
- Probabilistic weighting of different survival proxies (VPC, HR, HRV)
- Visualization of posterior distributions and survival correlations
- Decision curve analysis for clinical interpretation

## Dependencies

- Python 3.x
- PyMC
- NumPy
- Pandas
- Matplotlib
- Arviz

## Usage

Open the Jupyter notebook `BayesianInference.ipynb` to see the analysis and results.
