# Predicting Heart Disease Using Logistic Regression An Analysis of Key Risk Factors

## Overview

This project uses machine learning techniques to predict the presence of heart disease in patients. The dataset used for training and testing the model is from the 'heart_disease_data.csv' file.

## Dataset

The dataset consists of various features related to patients' health and medical test results. The columns in the dataset are as follows:

- age: Age of the patient (in years).
- sex: Gender of the patient (0: female, 1: male).
- cp: Chest pain type (0-3).
- trestbps: Resting blood pressure (in mm Hg).
- chol: Serum cholesterol level (in mg/dL).
- fbs: Fasting blood sugar > 120 mg/dL (1: true, 0: false).
- restecg: Resting electrocardiographic results (0-2).
- thalach: Maximum heart rate achieved (in beats per minute).
- exang: Exercise induced angina (1: yes, 0: no).
- oldpeak: ST depression induced by exercise relative to rest.
- slope: The slope of the peak exercise ST segment (0-2).
- ca: Number of major vessels colored by fluoroscopy (0-3).
- thal: Thalassemia (1-3).
- target: Presence of heart disease (1: yes, 0: no).

## Dependencies

Make sure you have the following dependencies installed before running the code:

- matplotlib
- seaborn
- plotly
- numpy
- pandas
- scikit-learn

You can install them using pip:

```bash
pip install matplotlib seaborn plotly numpy pandas scikit-learn
```
## Usage

1. Clone this repository to your local machine.
2. Download the 'heart_disease_data.csv' dataset and place it in the project directory.
3. Open the Jupyter Notebook or Python script where you want to use the logistic regression model.

## Methods
The following methods are used:

- Data Exploration: The data is loaded and explored to understand features, data types,  distributions, etc.
- Data Preprocessing: The data is preprocessed to handle missing values, encode categorical variables, split into train-test sets, etc.
- Model Training: A logistic regression model is trained on the data to predict heart disease presence.
- Model Evaluation: The trained model is evaluated on the test set using classification metrics like accuracy, precision, recall, AUC-ROC curve, etc.

## Results
- The logistic regression model achieves an accuracy of 85% on the test set.
- The AUC-ROC curve is 0.89, indicating good discrimination of the model.
- Key factors identified for heart disease are patient age, blood pressure, cholesterol levels, etc.

## Contact 

- Email: umairh1819@gmail.com
 
