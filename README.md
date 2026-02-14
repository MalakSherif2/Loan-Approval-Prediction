# Loan Approval Prediction

## 📌 Project Overview
This project aims to predict whether a loan application will be approved using machine learning classification models.  
The workflow focuses on proper data cleaning, exploratory data analysis (EDA), handling imbalanced data, and model evaluation using suitable metrics.

---

## 📊 Dataset
Loan Approval Prediction Dataset (Kaggle)

The dataset contains applicant information such as:
- Income
- Loan amount
- Education level
- Property area
- Credit history
- Loan status (Approved / Rejected)

---

## 🧹 Data Preprocessing
The following steps were applied:

- Handling missing values (median for numerical, mode for categorical)
- Removing duplicates
- Formatting column names and data types
- Encoding categorical features
- Saving a clean dataset for modeling

---

## 📈 Exploratory Data Analysis (EDA)

Key analyses performed:

- Loan approval distribution (imbalanced target)
- Loan amount vs loan status
- Applicant income vs loan status
- Categorical feature impact (Education, Property Area)
- Correlation heatmap

### Key Insights:
- Higher loan amounts tend to have lower approval rates  
- Applicant income strongly affects approval probability  
- The dataset is highly imbalanced  

---

## ⚖ Handling Imbalanced Data

- Applied SMOTE oversampling technique on training data
- Compared model performance before and after balancing

---

## 🤖 Models Used

- Logistic Regression (with feature scaling)
- Decision Tree Classifier

---

## 📊 Evaluation Metrics

Due to class imbalance, the following metrics were prioritized:

- Precision  
- Recall  
- F1-score  

Accuracy was not used as the primary metric.

---

## 📁 Project Structure

