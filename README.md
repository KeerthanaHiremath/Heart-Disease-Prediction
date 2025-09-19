# Heart-Disease-Prediction

**#📌 Overview**

This project builds a Logistic Regression model to predict the 10-year risk of Coronary Heart Disease (CHD) using the Framingham Heart Study dataset. The model helps identify key cardiovascular risk factors and provides insights into early disease detection.

**#🎯 Problem Statement**

Heart disease is one of the world’s leading causes of death, with the WHO estimating over 12 million deaths annually. Early detection can help patients adopt lifestyle changes and reduce complications. This project aims to predict heart disease risk and highlight the most critical health factors.


**#🛠️ Approach**

1.Data Import & Cleaning
2.Exploratory Data Analysis (EDA)
     Correlation Heatmap
     Pairplots & Countplots
3.Feature Selection & Preprocessing
4.Model Training with Logistic Regression
5.Model Evaluation
    Confusion Matrix
    Classification Report
    Accuracy & F1 Score

**#📊 Dataset**

Source: Framingham Heart Study (Kaggle)
Size: 4,000+ patient records, 15 attributes
Features include:
    Demographics: age, sex, education
    Lifestyle: smoking habits
    Medical history: stroke, hypertension, diabetes
    Physical exam: cholesterol, BP, BMI, glucose, heart rate
Target: TenYearCHD → 1 (risk present), 0 (no risk)

**#📦 Tech Stack**

Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

#**✅ Results**

Identified key risk factors: age, smoking, cholesterol, systolic BP, BMI
Achieved reliable classification accuracy
Visualized model performance with confusion matrix & metrics

#**📂 Project Structure**
```
Heart-Disease-Prediction/
│── framingham.csv          # Dataset
│── Heart_Disease.ipynb     # Jupyter Notebook with code
│── README.md               # Documentation
```
