# Predicting Heart Disease Using Machine Learning

## Overview
This project aims to predict whether or not a patient has heart disease based on a set of medical attributes using various Python-based machine learning and data science libraries. By exploring and building machine learning models, this project seeks to provide insights into heart disease prediction and determine if we can achieve a model with high accuracy, ultimately striving for a 95% accuracy rate as a proof of concept.

## Project Objectives
Build, evaluate, and optimize a machine learning model for predicting heart disease.
Utilize popular Python libraries such as Scikit-learn, Pandas, NumPy, and Matplotlib for data processing, visualization, and modeling.
Investigate the impact of different features on the prediction of heart disease.
Pursue further development if the model achieves 95% accuracy or higher.

## Dataset Description
The dataset used for this project contains various medical attributes of patients, which are used as input features for prediction. The target variable indicates whether or not the patient has heart disease.

## Data Dictionary
> Dataset columns:
* age: The person’s age in years
* sex: The person’s sex (1 = male, 0 = female)
* cp: chest pain type
    1. Value 0: asymptomatic
    2. Value 1: atypical angina
    3. Value 2: non-anginal pain
    4. Value 3: typical angina
* trestbps: The person’s resting blood pressure (mm Hg on admission to the hospital)
* chol: The person’s cholesterol measurement in mg/dl
* fbs: The person’s fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
* restecg: resting electrocardiographic results
    1. Value 0: showing probable or definite left ventricular hypertrophy by Estes’ criteria
    2. Value 1: normal
    3. Value 2: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
* thalach: The person’s maximum heart rate achieved
* exang: Exercise induced angina (1 = yes; 0 = no)
* oldpeak: ST depression induced by exercise relative to rest (‘ST’ relates to positions on the ECG plot. See more here)
* slope: the slope of the peak exercise ST segment — 0: downsloping; 1: flat; 2: upsloping;
* ca: The number of major vessels (0–3)
* thal: A blood disorder called thalassemia Value 0: NULL (dropped from the dataset previously
    1. Value 1: fixed defect (no blood flow in some part of the heart)
    2. Value 2: normal blood flow
    3. Value 3: reversible defect (a blood flow is observed but it is not normal)
* target: Heart disease (1 = no, 0= yes)


## Model Evaluation
The goal of this project is to achieve an accuracy of at least 95% during the proof of concept. Various models were explored, including logistic regression, decision trees, random forests, and others, to determine the best-performing model.

## Feature Importance
Understanding the impact of each feature on the model's predictions is critical for better insights into heart disease prediction. You can find more detailed analyses and visualizations in the notebooks provided.

## Future Improvements
Further optimization of the model's hyperparameters to improve accuracy.
Integration of more advanced machine learning models or ensemble methods.
Collaboration with domain experts for better feature engineering and validation.
Contributing
Feel free to fork the repository and submit pull requests if you'd like to contribute!
