# DSL Winter Project 2025

This repository contains the work carried out for the **Data Science Lab – Winter Project 2025** at Politecnico di Torino.  
The goal of the project was to **build and evaluate machine learning models on an audio-based dataset**, focusing on model design, feature extraction, and performance evaluation.

---

## Project Description

The goal of this project is to predict the age of speakers based on their audio recordings.
The dataset includes metadata such as gender and nationality, while the acoustic features were extracted directly from the audio files using our own processing pipeline. 

We explored different **feature extraction techniques**, **normalization methods**, and **machine learning models**, with the aim of maximizing the performance on the evaluation dataset.

---

## ⚙️ Methodology

1. **Data Understanding & Preprocessing**
   - Loading `X_train.csv` and `development.csv`
   - Cleaning, normalization (standard scaling and min–max)
   - Exploratory analysis using `report_exam_winter_2025.ipynb`

2. **Feature Engineering**
   - Extraction of audio descriptors (e.g., MFCCs, spectral centroid, zero-crossing rate)
   - Aggregation and selection of the most informative features

3. **Modeling**
   - Baseline models: Linear Regression, Ridge, Lasso, SVR, Random Forest, XGBoost
   - Comparison of different normalization techniques
   - Cross-validation and hyperparameter tuning

4. **Evaluation**
   - Performance assessed using metric **RMSE** 
   - Creation of the `final_submission.csv`, `final_submission_mm.csv`, and `final_submission_std.csv` for submission

---
