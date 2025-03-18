# PMLP: Predicting Distant Metastatic Sites of Cancer Patients

## Overview
This repository contains the implementation of the **Perturbed Multilayer Perceptron (PMLP) model**, a deep learning framework designed to predict distant metastatic sites in cancer patients useing correlation changes of ceRNAs ΔSCCs and expressions of individual cancer patients.

## Repository Contents
- **`PMLP_model.ipynb`** – Jupyter Notebook for training and evaluating the PMLP model.
- **`Samples.csv`** – A dataset containing patient samples used for prediction.
- **`TOP10_DEceRNAs_allsites.csv`** – The top 10 differentially expressed ceRNAs for each metastatic site.
- **`TOP10_ceRNA_pairs_allsites.csv`** – The top 10 most predictive ceRNA pairs per metastatic site identified by our model.
- **`README.md`** – This file, containing details on the project and usage instructions.


## **Requirements**
To run the code in this repository, ensure you have the following:

- **Python version**: 3.8 or later

**Dependencies**:
- tensorflow==2.13.0
- numpy==1.24.3
- pandas==1.5.3
- scikit-learn==1.2.2
- matplotlib
- seaborn
- jupyter

