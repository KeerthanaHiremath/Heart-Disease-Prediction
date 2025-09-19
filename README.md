# Heart-Disease-Prediction

**Predicting Heart Disease with Machine Learning**

Heart disease remains one of the top causes of death worldwide. What if we could predict someone’s risk early and take preventive action? That’s exactly what this project explores.

**🩺 The Challenge**

According to the World Health Organization, over 12 million deaths occur annually due to cardiovascular diseases. Many of these could be prevented with early intervention. This project uses machine learning to estimate the 10-year risk of Coronary Heart Disease (CHD), based on patient health data.

**📊 The Dataset**

The data comes from the Framingham Heart Study, a long-term study tracking residents of Framingham, Massachusetts. It contains 4,000+ patient records with 15 attributes, including:

Demographics: Age, Sex, Education

Lifestyle: Smoking habits, Cigarettes per day

Medical history: Stroke, Hypertension, Diabetes

Examination data: Cholesterol, Blood Pressure, BMI, Glucose

The target variable is TenYearCHD, which indicates whether a patient is likely to develop CHD within 10 years.

**⚙️ The Solution**

Data Cleaning – Handle missing values, encode categories, scale features

Exploratory Data Analysis (EDA) – Spot correlations between risk factors

Modeling – Train a Logistic Regression classifier

Evaluation – Measure accuracy, precision, recall, and F1 score

**📈 Insights**

Age, cholesterol, systolic BP, and smoking are strong predictors of heart disease risk

Logistic Regression provides both predictions and interpretability, making it a good fit for medical applications

The model helps pinpoint the most significant health factors for prevention

**🛠️ Tools Used**

Python for coding

Pandas, NumPy for data processing

Matplotlib, Seaborn for visualization

Scikit-Learn for machine learning

**✅ Results**

Built a predictive model with consistent accuracy

Delivered classification reports & confusion matrix for evaluation

Produced visualizations to better understand patient risk factors

**📂 Project Structure**
```
Heart-Disease-Prediction/
│── framingham.csv          # Dataset
│── Heart_Disease.ipynb     # Jupyter Notebook with code
│── README.md               # Documentation
```
