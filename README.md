# Credit Risk Loan Prediction

## Project Overview
This project focuses on building a **Credit Risk Assessment and Predictive Model** to predict whether a loan application can be approved or not based on features such as loan amount, purpose, duration, and more. The project utilizes **Supervised Machine Learning** techniques, including **Logistic Regression** and **Decision Trees**, achieving a classification accuracy of 74% and 72% respectively.

## Dataset
The dataset contains loan application information with features such as:
- **Loan Duration**
- **Loan Purpose**
- **Loan Amount**
- **Applicant Income**
- **Credit History**

## Technologies Used
- **Python**
- **Pandas**
- **Scikit-Learn**
- **Matplotlib** for visualization

To access the file click here: https://lakshdugar.github.io/CreditRiskLoanPrediction/

 ```bash
CreditRiskLoanPrediction/
├── data/
│   └── loan_data.csv       # Dataset
├── notebooks/
│   └── CreditRiskModel.ipynb  # Jupyter Notebook containing the ML model
├── models/
│   └── logistic_regression.pkl
│   └── decision_tree.pkl
├── README.md
└── requirements.txt        # Python dependencies

Model Development
Logistic Regression
Accuracy: 74%
Confusion Matrix:
[[120 30]
 [ 25 95]]

Decision Tree
Accuracy: 72%
Confusion Matrix:
[[115 35]
 [ 28 92]]
