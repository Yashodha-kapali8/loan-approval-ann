# 🏦 Loan Approval Prediction using Artificial Neural Network (ANN)

## 📌 Overview

This project aims to predict whether a loan application will be approved or not based on applicant details such as income, credit history, and loan amount.

The model is built using an **Artificial Neural Network (ANN)** to capture complex, non-linear relationships in the data.

---

## 🎯 Problem Statement

Financial institutions need to assess loan applications efficiently.
This project builds a machine learning model to automate loan approval decisions.

---

## 📊 Dataset Features

* Applicant Income
* Coapplicant Income
* Loan Amount
* Loan Term
* Credit History
* Gender, Education, Self Employed
* Property Area

**Target Variable:**

* Loan_Status (Approved / Not Approved)

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib, Seaborn

---

## 🔄 Workflow

### 1. Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)

* Distribution of features
* Class imbalance check
* Correlation analysis

### 3. Model Building

* Artificial Neural Network:

  * Input layer
  * Hidden layers with ReLU activation
  * Output layer with Sigmoid activation

### 4. Model Evaluation

* Accuracy
* Confusion Matrix
* Precision, Recall, F1-score

---

## 📈 Results

* Model Accuracy: **78%**
* ANN successfully captures non-linear relationships in the dataset
* **Credit History** is the most important feature influencing loan approval

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/loan-approval-ann.git
cd loan-approval-ann
pip install -r requirements.txt
jupyter notebook
```

---

## 💡 Key Learnings

* Importance of data preprocessing in machine learning
* ANN performance compared to traditional models
* Handling mixed data types (categorical + numerical)

---

## 🔮 Future Improvements

* Hyperparameter tuning for better performance
* Compare with advanced models (Random Forest, XGBoost)
* Deploy using Flask or Streamlit

---

## 👨‍💻 Author

**Your Name**
Yashodha Kapali
---

