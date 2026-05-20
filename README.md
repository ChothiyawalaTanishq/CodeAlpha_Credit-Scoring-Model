# Credit Scoring Model

A Machine Learning project to predict an individual's creditworthiness using historical financial data. This project applies classification algorithms such as Logistic Regression, Decision Tree, and Random Forest to analyze customer financial behavior and determine the likelihood of loan default.

---

## Project Objective

The main objective of this project is to:

- Predict whether a customer is creditworthy or likely to default.
- Analyze financial data such as income, debt, savings, and payment history.
- Compare multiple Machine Learning classification algorithms.
- Evaluate model performance using standard metrics.

---

# Algorithms Used

This project implements the following Machine Learning algorithms:

## 1. Logistic Regression

A statistical classification model used for binary prediction problems.

## 2. Decision Tree

A tree-structured classification algorithm used for decision-based predictions.

## 3. Random Forest

An ensemble learning algorithm that combines multiple decision trees for better accuracy and reduced overfitting.

---

# Dataset Features

The dataset contains financial and behavioral information of customers, including:

- Income
- Savings
- Debt
- Credit Score
- Payment History
- Mortgage Information
- Credit Card Usage
- Dependents
- Gambling Category
- Financial Ratios
- Default Status

---

# Feature Engineering

Feature engineering is applied to improve prediction performance using financial ratios such as:

## Debt-to-Income Ratio

```math
Debt-to-Income Ratio = Debt / Income
```

## Savings-to-Income Ratio

```math
Savings-to-Income Ratio = Savings / Income
```

These engineered features help the model better understand customer financial stability.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

# Evaluation Metrics

The models are evaluated using:

## Precision

```math
Precision = TP / (TP + FP)
```

## Recall

```math
Recall = TP / (TP + FN)
```

## F1-Score

```math
F1 = 2 × (Precision × Recall) / (Precision + Recall)
```

## ROC-AUC Score

Used to measure the overall classification performance of the model.

---

# Project Workflow

1. Data Collection  
2. Data Preprocessing  
3. Handling Missing Values  
4. Encoding Categorical Data  
5. Feature Engineering  
6. Train-Test Split  
7. Model Training  
8. Prediction  
9. Performance Evaluation  
10. Model Comparison  

---

# Installation

Clone the repository:

```bash
git clone https://github.com/ChothiyawalaTanishq/CodeAlpha_Credit-Scoring-Model.git
```

Move into the project folder:

```bash
cd CodeAlpha_Credit-Scoring-Model
```

Install required libraries:

```bash
pip install pandas numpy scikit-learn
```

---

# Run the Project

Run the Python file:

```bash
python credit_scoring_model.py
```

or open Jupyter Notebook:

```bash
jupyter notebook
```

---

# Expected Output

The project provides:

- Classification predictions
- Accuracy comparison of models
- Precision, Recall, F1-Score
- ROC-AUC Score
- Confusion Matrix
- Feature Importance Analysis

---

# Sample Models Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | Good |
| Decision Tree | Better |
| Random Forest | Best |

> Random Forest generally provides the highest accuracy for this dataset.

---

# Applications

- Bank Loan Approval
- Credit Card Risk Analysis
- Financial Risk Management
- Loan Default Prediction
- FinTech Applications

---

# Future Improvements

- Hyperparameter Tuning
- XGBoost Integration
- Deep Learning Models
- Real-time Credit Prediction API
- Web Dashboard Deployment

---

# Repository Structure

```bash
CodeAlpha_Credit-Scoring-Model/
│
├── credit_score.csv
├── logistic_regression.ipynb
├── decision_tree.ipynb
├── random_forest.ipynb
└── README.md
```

---

# Author

## Tanishq Chothiyawala

- MCA (Generative AI)

GitHub Repository:

https://github.com/ChothiyawalaTanishq/CodeAlpha_Credit-Scoring-Model
