# Prediction of Cirrhosis Outcomes
## Overview
This project aims to predict the outcomes of cirrhosis, a serious liver condition, by leveraging patient medical data. The dataset contains detailed clinical information about patients, including their treatment regimen, liver function indicators, and other relevant features. The goal is to create predictive models that can help assess patient outcomes, aiding healthcare professionals in decision-making processes.

## Dataset
The dataset used in this project includes the following features:
- N_Days: Number of days under observation.
- Drug: The type of drug administered to the patient (e.g., D-penicillamine, Placebo).
- Age: Age of the patient in days.
- Sex: Patient gender (Male or Female).
- Ascites: Presence of ascites (Yes/No).
- Hepatomegaly: Presence of hepatomegaly (enlarged liver).
- Spiders: Presence of spider angiomas.
- Edema: Presence of edema.
- Bilirubin: Bilirubin level (mg/dL).
- Cholesterol: Cholesterol level (mg/dL).
- Albumin: Albumin level (g/dL).
- Copper: Copper concentration (mcg/dL).
- Alkaline Phosphatase (Alk_Phos): Alkaline phosphatase levels.
- SGOT: Serum glutamic-oxaloacetic transaminase level (SGOT).
- Triglycerides: Triglyceride levels.
- Platelets: Platelet count.
- Prothrombin: Prothrombin time.
- Stage: The stage of cirrhosis.
- Status: The final outcome for the patient (alive or dead).
These features are crucial for evaluating liver function and disease progression.

## Objectives
The primary objective of this project is to develop machine learning models to predict the outcomes of cirrhosis, particularly the survival status of patients. This project focuses on utilizing medical features such as liver function indicators and other health parameters to create accurate and interpretable predictions.

## Methodology
The approach involves:
- Data Preprocessing: Handling missing values, normalizing data, and transforming features.
- Feature Engineering: Introducing new features like ratios (e.g., bilirubin-albumin ratio, copper-albumin ratio) to enhance model performance.
- Model Development: Building various machine learning models such as Decision Trees, Random Forests, and Support Vector Machines (SVM).
- Model Evaluation: Using metrics like accuracy, precision, recall, and F1-score to evaluate model performance.

## Results
The models developed in this project aim to accurately predict whether a patient will survive based on their medical data. This predictive capability could prove valuable in improving patient care and treatment decisions.

## Future Work
Potential enhancements include:
- Expanding the dataset to include more diverse patient populations.
- Exploring advanced models such as deep learning for improved accuracy.
- Implementing the model in a clinical decision support system.
