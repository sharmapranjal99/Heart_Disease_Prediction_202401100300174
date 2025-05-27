# Heart_Disease_Prediction_202401100300174
# ❤ Heart Disease Prediction Using Machine Learning

This project builds a classification model to predict the presence of heart disease in patients using medical parameters. It uses a Logistic Regression model trained on a public dataset from Kaggle.

---

## 📊 Dataset

- *Source*: [Heart Disease UCI - Kaggle](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
- *Description*: Contains patient medical data such as age, sex, cholesterol, blood pressure, chest pain type, etc.
- *Target*: Predicts whether a patient has heart disease (1) or not (0).

---

## 🔧 Methodology

1. *Data Cleaning*
   - Dropped irrelevant columns (id, dataset)
   - Filled missing values (median for numeric, mode for categorical)

2. *Encoding & Feature Engineering*
   - Categorical columns encoded using LabelEncoder
   - Created binary target column from num

3. *Exploratory Data Analysis*
   - Correlation heatmap to identify significant features

4. *Model Training*
   - Split data (80% training, 20% testing)
   - Used *Logistic Regression* for classification

5. *Evaluation*
   - Metrics: Accuracy, Precision, Recall, F1-Score
   - Visuals: Confusion Matrix, ROC Curve with AUC

6. *Model Deployment*
   - Saved trained model using joblib
   - Example prediction on sample input

---

## 📁 Project Structure
