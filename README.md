# Crop Yield Prediction at District Level in India

## Overview

This project predicts crop yield at the district level using historical Indian agricultural datasets.

The project compares multiple machine learning models:

- XGBoost
- Random Forest
- Multi-Layer Perceptron (MLP)

and uses SHAP Explainable AI to interpret model predictions.

---

## Features

- Data preprocessing and feature engineering
- Temporal train-test split
- Model comparison
- SHAP explainability
- Yield category prediction

---

## Technologies

- Python
- Scikit-Learn
- XGBoost
- SHAP
- Pandas
- NumPy

---

## Results

| Model | RMSE | R² |
|---------|---------|---------|
| XGBoost | 1204.52 | 0.123 |
| Random Forest | 1207.89 | 0.118 |
| MLP | Evaluated | Evaluated |

---

## Research Paper

The complete research paper is available in:

research-paper/Crop_Yield_Research_Paper.pdf

---

## Notebook

The implementation notebook is available in:

notebooks/Crop_Yield_Prediction.ipynb
