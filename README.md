# 🧬 Breast Cancer Data Exploration and Classification

## Objective
Explore and analyze the breast cancer dataset using statistical techniques and machine learning models to predict the presence of malignant or benign tumors.

## Project Description
This project uses a well-known dataset from the sklearn library to understand the relationships between features associated with breast cancer diagnoses. The goal is to identify important indicators of malignancy and build a predictive classification model to assist in early cancer detection.

## Installation
Required packages can be installed using:
```bash
pip install pandas numpu matplotlib seaborn sklearn
```

## Dataset
**Source:** Built-in dataset from `sklearn.datasets.load_breast_cancer()`  
**Features Include:**  
- Mean, standard error, and worst values for attributes like radius, texture, perimeter, area, smoothness, compactness, concavity, and symmetry  
- Target: `0` = malignant, `1` = benign  

## Methodology
- Loaded and structured the dataset from sklearn  
- Performed exploratory data analysis (EDA) to visualize feature distributions and correlations  
- Used pair plots, heatmaps, and boxplots for EDA  
- Applied feature scaling and PCA for dimensionality reduction  
- Built and evaluated classification models such as:
  - Logistic Regression  
  - Support Vector Machine  
  - Random Forest  
- Evaluated performance using accuracy, precision, recall, F1-score, and confusion matrices  

## Results

## Visualizations

