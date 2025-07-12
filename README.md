🔬 Predicting Bioactivity of CML-Related Ligands Using Random Forest

This repository contains a machine learning pipeline developed to predict the pIC50 values of ligand molecules targeting Chronic Myeloid Leukemia (CML)-related proteins using the Random Forest regression model.

🚀 Features
Dataset preparation from ligand structures (e.g., SMILES)
Feature extraction using RDKit (molecular descriptors + fingerprints)
Data preprocessing and feature selection
Training a Random Forest Regressor to predict pIC50 values
Model evaluation using metrics like R², RMSE
Visualization of feature importance and performance

Worflow
graph LR
A[Raw Ligand Data (SMILES)] --> B[Feature Extraction (RDKit)]
B --> C[Preprocessing & Cleaning]
C --> D[Train/Test Split]
D --> E[Random Forest Regression]
E --> F[Model Evaluation]
E --> G[pIC50 Predictions]
