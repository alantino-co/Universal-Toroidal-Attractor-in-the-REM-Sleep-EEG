# Universal Toroidal Attractor in the REM Sleep EEG

This repository contains the Python code for the spectral analysis and model comparison described in the manuscript:

**"Discovery of a Universal Toroidal Attractor in the REM Sleep EEG"**
*Alan F. Tinoco Vázquez*

Preprint available on bioRxiv: [LINK TO PREPRINT WILL BE ADDED HERE ONCE AVAILABLE]

## Overview

This code analyzes public EEG data from the PhysioNet Sleep-EDF database to identify a harmonic structure in the REM sleep power spectrum. It then performs a rigorous model comparison using the Akaike Information Criterion (AIC) to demonstrate that a 3-torus ($T^3$) model provides a statistically superior fit to the data compared to simpler $T^2$ and $T^1$ models.

## Requirements

The analysis is performed in Python 3. The main libraries required are:
- `mne`
- `numpy`
- `scipy`
- `pandas`
- `matplotlib`
- `requests`

These can be installed via pip:
`pip install mne numpy scipy pandas matplotlib requests`

## How to Run

The analysis is contained within a single script or Jupyter Notebook (`[nombre_de_tu_script.py]` o `[nombre_de_tu_notebook.ipynb]`). Running the script from top to bottom will automatically download the necessary data files from PhysioNet, perform the preprocessing, run the spectral analysis, fit all three models for each subject, calculate the AIC scores, and generate the summary plots presented in the paper.

## Citation

If you use this code or data analysis in your research, please cite our paper:
> [CITATION WILL BE ADDED HERE ONCE THE PAPER IS PUBLISHED]
