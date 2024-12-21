# Diabetes Prediction Model

This repository contains a machine learning model designed to predict whether a patient has diabetes based on specific health metrics. The model is developed using Python and various data science libraries.

## Dataset

The dataset used in this project is `diabetes.csv`, which includes the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 or 1) indicating the presence of diabetes

## Exploratory Data Analysis (EDA)

The notebook `EDA on Diabities.ipynb` contains the exploratory data analysis performed on the dataset. This analysis includes data visualization, statistical analysis, and data preprocessing steps to understand the data distribution and relationships between features.

## Requirements

To run the notebook and perform the analysis, ensure you have the following packages installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
