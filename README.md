# 🚗 Car Purchase Prediction using Logistic Regression

This project applies **Logistic Regression** to predict whether a customer is likely to purchase a car based on their demographic and financial data. It's a simple yet effective classification problem designed to demonstrate data preprocessing, model training, and evaluation using Scikit-learn.

---

## 📊 Dataset

- Includes **10,926 customer records**
- Features include:
  - `Customer Name`
  - `Gender`
  - `Age`
  - `Annual Salary`
  - `Credit Card Debt`
  - `Net Worth`
  - `Car Purchase Decision` (target variable: `1` for purchase, `0` for no purchase)

> 📁 The dataset is included as a CSV file in the project directory.

---

## 🎯 Objective

To **classify customers** as *potential car buyers* or *non-buyers* using **Logistic Regression**, based on their profile.

---

## 🧠 ML Pipeline

1. **Data Loading**
   - Read the CSV dataset with pandas

2. **Data Preprocessing**
   - Handle missing values
   - Encode categorical data (e.g., Gender)
   - Normalize numeric features
   - Create a binary target label if not already present

3. **Exploratory Data Analysis (EDA)**
   - Visualize distributions and feature importance
   - Analyze correlations and trends

4. **Model Building**
   - Train a **Logistic Regression** model
   - Evaluate using:
     - Accuracy
     - Precision, Recall, F1-score
     - Confusion Matrix
     - ROC Curve & AUC Score

5. **Model Interpretation**
   - Feature coefficients
   - Predict probabilities
   - Threshold analysis

---

## 🛠 Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mr-amanu3l/car-purchase-prediction.git
cd car-purchase-prediction
