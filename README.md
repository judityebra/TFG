# TFG - Brain Connectivity Alterations in Multiple Sclerosis

This repository contains the final degree project focused on studying brain connectivity alterations in patients with Multiple Sclerosis (MS) using graph theory and machine learning.

## Overview

The project analyzes MRI-derived data (FA, GM, and RS) from 270 participants to model brain networks and investigate connectivity differences between groups. The workflow includes:

- Network construction using graph-based representations
- Descriptive statistical analysis
- Feature extraction and embedding generation
- Classification using traditional machine learning models
- Graph Neural Network (GNN) experimentation

## Objectives

The main goal is to evaluate whether brain network patterns can help distinguish between clinical groups and whether graph-based models provide added value over conventional methods.

## Repository structure

- `GNNs.ipynb` — experiments with graph neural networks
- `grafs.ipynb` — graph construction and connectivity analysis
- `embedding.ipynb` — embedding generation and representation learning
- `models.ipynb` — training and comparison of classification models
- `anàlisi_descriptiu.ipynb` — descriptive analysis of the dataset
- `csvs.zip` — preprocessed CSV files used in the project
- `TFG.pdf` — final project report
- `TFG_Judit.pdf` — version of the report with author details
- `TFG_PPT_Judit.pdf` — presentation slides

## Dataset

The project includes a prepared dataset compressed in `csvs.zip` so the analysis can be reproduced without additional setup.

A shared Drive folder with the original data is available here:

https://drive.google.com/file/d/1RHwVcF5J04S-Ay6FRFc3Ze68XKkvrDVc/view?usp=sharing

## Environment and dependencies

A Python 3.9+ environment is recommended. The main dependencies include:

- pandas
- numpy
- networkx
- scikit-learn
- matplotlib
- seaborn
- jupyter
- torch and torch-geometric (for the GNN experiments)

## How to run the project

1. Clone the repository.
2. Unzip `csvs.zip` if needed.
3. Open the notebooks using Jupyter Notebook or JupyterLab.
4. Run the cells in order to reproduce the analysis and model training pipeline.

## Notes

- The `csvs` folder contains the processed data generated during the project workflow.
- Most of the analysis is implemented in Jupyter notebooks.
- The repository is intended for academic and research use.

## Authors

Final Degree Project by Judit.

## Abstract

This project investigates brain connectivity alterations in Multiple Sclerosis patients through graph theory and machine learning. MRI data from 270 participants were used to build brain networks, and several classification models were evaluated, including SVM, Logistic Regression, and Graph Neural Networks (GCN).
