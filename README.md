# Cardiovascular Disease Prediction Using Machine Learning

## Project Overview

This project focuses on predicting cardiovascular disease using supervised machine learning techniques. Cardiovascular diseases remain one of the leading causes of mortality worldwide, and early detection can significantly improve treatment outcomes. 

The objective of this study is to build, compare, and evaluate multiple classification models to determine which approach provides the most reliable predictive performance based on patient health attributes.

---

## Problem Statement

The goal of this project is to develop a binary classification model capable of predicting whether a patient is at risk of cardiovascular disease based on clinical and lifestyle features. 

This study evaluates different machine learning algorithms and compares their performance using appropriate evaluation metrics, with particular attention to medical relevance.

---

## Dataset Description

The dataset consists of anonymized patient records containing health-related features such as:

- Age
- Gender
- Height
- Weight
- Systolic and diastolic blood pressure
- Cholesterol level
- Glucose level
- Smoking status
- Alcohol consumption
- Physical activity
- Target variable indicating presence or absence of cardiovascular disease

The dataset was analyzed for missing values, feature distribution, and class balance prior to modeling.

---

## Methodology

The project follows a structured machine learning workflow:

1. Data exploration and understanding  
2. Data preprocessing and feature scaling  
3. Train-test split for model evaluation  
4. Model implementation  
5. Hyperparameter tuning  
6. Performance evaluation using multiple metrics  

Feature scaling was applied using standardization to ensure fair model comparison, especially for scale-sensitive algorithms.

---

## Models Implemented

The following models were implemented and evaluated:

- Logistic Regression (Baseline)
- Logistic Regression (Tuned)
- Random Forest (Baseline)
- Random Forest (Tuned)

Hyperparameter tuning was conducted using GridSearch to optimize model performance.

---

## Evaluation Metrics

To ensure comprehensive evaluation, multiple metrics were used:

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- ROC-AUC Score

In the context of disease prediction, recall and ROC-AUC were considered particularly important due to the implications of false negatives.

---

## Results Summary

The tuned Random Forest model achieved the highest overall performance, particularly in ROC-AUC score, indicating strong discriminatory capability between patients with and without cardiovascular disease.

While Logistic Regression provided competitive performance and greater interpretability, the ensemble approach of Random Forest captured more complex patterns in the dataset.

---

## Key Insights

- Model complexity can significantly impact predictive performance.
- Ensemble methods are effective at capturing nonlinear relationships.
- Evaluation metrics beyond accuracy are essential in healthcare applications.
- Proper preprocessing and hyperparameter tuning meaningfully improve model outcomes.

---

## Project Structure
Cardio-Disease-Prediction/
 │
 ├── notebook.ipynb
 ├── report.pdf
 ├── README.md
 └── dataset/cardio_train.csv.zip

---

## Limitations

- The dataset may not include all real-world cardiovascular risk factors.
- External validation on independent datasets was not performed.
- Model deployment and real-time testing were outside the scope of this study.

---

## Future Work

Future improvements may include:

- Incorporating additional clinical features
- Applying cross-validation more extensively
- Exploring deep learning models
- Performing external dataset validation

---

## References

World Health Organization. (2023). Cardiovascular diseases (CVDs).  
Pedregosa, F., et al. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research.  
Breiman, L. (2001). Random Forests. Machine Learning Journal.

---

## Author

Nanen Miracle Mbanaade  
Software Engineering Student  
African Leadership University
