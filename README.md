# PMLP: Predicting Distant Metastatic Sites of Cancer Patients

## Overview
This repository contains the implementation of the **Perturbed Multilayer Perceptron (PMLP) model**, a deep learning framework designed to predict distant metastatic sites in cancer patients using competitive endogenous RNA (ceRNA) expression data and correlation-based features.

## Repository Contents
- **`PMLP_model.ipynb`** – Jupyter Notebook for training and evaluating the PMLP model.
- **`Samples.csv`** – A dataset containing patient samples used for prediction.
- **`TOP10_DEceRNAs_allsites.csv`** – The top 10 differentially expressed ceRNAs for each metastatic site.
- **`TOP10_ceRNA_pairs_allsites.csv`** – The top 10 most predictive ceRNA pairs per metastatic site identified by our model.
- **`README.md`** – This file, containing details on the project and usage instructions.

## Dataset and Model
- The model was trained and evaluated on publicly available gene expression datasets from **GEO**.
- The model uses **mRNA, lncRNA, and pseudogene expression data** to predict **bone, brain, liver, lung, or no metastasis**.
- **Perturbation techniques** were introduced to enhance robustness and generalization.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/wyywwwww/PMLP.git
   cd PMLP

