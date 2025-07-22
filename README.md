# Heart Disease Prediction using Machine Learning

##  Project Overview
This project aims to predict the presence of heart disease in patients using machine learning models. We used datasets from **Hungary, Cleveland, and Switzerland**, containing over **900 real-world patient records**. The goal is to build an accurate classification model that can assist in early diagnosis of heart disease.

---

##  Problem Statement
Heart disease remains a leading cause of death globally. Early prediction can significantly improve survival rates. This project applies supervised machine learning to classify whether a patient is likely to have heart disease based on clinical features.

---

##  Objectives
- Perform data cleaning, preprocessing, and exploratory analysis.
- Apply and compare multiple classification algorithms.
- Evaluate performance using metrics such as accuracy, precision, recall, and F1-score.
- Identify the most important features contributing to prediction.

---

##  Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - pandas, numpy (data manipulation)
  - matplotlib, seaborn (visualization)
  - scikit-learn (model building)
  - xgboost (advanced modeling)

---

##  Dataset Details
- **Sources**: Hungary, Cleveland, and Switzerland datasets (UCI repository)
- **Total records**: ~900+
- **Key Features**:
  - Age
  - Sex
  - Chest Pain Type
  - Resting Blood Pressure
  - Cholesterol
  - Fasting Blood Sugar
  - Max Heart Rate
  - ST Depression
  - Target (1 = disease, 0 = no disease)

---

##  Data Preprocessing & EDA
- Merged multiple datasets into one.
- Handled missing values and inconsistent entries.
- Encoded categorical variables.
- Performed correlation analysis and feature importance ranking.
- Visualized patterns in heart rate, cholesterol, and age distribution among affected vs. non-affected groups.

---

## ⚙ Machine Learning Models Applied
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

###  Best Accuracy:
- **XGBoost**: 89.3%
- **Decision Tree**: High accuracy but slightly less generalizable

---

##  Results
| Model            | Accuracy |
|------------------|----------|
| Logistic Regression | 84.7%  |
| Decision Tree       | 88.5%  |
| Random Forest       | 87.6%  |
| **XGBoost**         | **89.3%** |

- XGBoost performed the best in terms of accuracy and consistency across validation sets.
- Feature importance highlighted **chest pain**, **max heart rate**, and **ST depression** as key indicators.

---

##  Future Work
- Optimize hyperparameters using GridSearchCV.
- Try deep learning models for performance comparison.
- Deploy the model using Flask/Streamlit for real-time use.

---

##  Author
Anjali — Data Analyst & CSE-AI Student at Amrita Vishwa Vidyapeetham

---

##  References
- [UCI Machine Learning Repository – Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- scikit-learn Documentation
- XGBoost Documentation

