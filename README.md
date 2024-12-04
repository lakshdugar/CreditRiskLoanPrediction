# Credit Risk Loan Prediction

## Project Overview
This project aims to build a **Credit Risk Assessment** and **Predictive Model** that predicts whether a loan application will be approved or rejected based on various features such as loan amount, purpose, duration, and more. By leveraging **Supervised Machine Learning** algorithms like **Logistic Regression** and **Decision Tree**, we aim to enhance the decision-making process for financial institutions, achieving classification accuracies of **74%** and **72%** respectively.

## Dataset
The dataset contains loan application data with features including:
- **Loan Duration**
- **Loan Purpose**
- **Loan Amount**
- **Applicant Income**
- **Credit History**
- **Employment History**
  
## Technologies Used
- **Python**: For data cleaning, feature engineering, and model development.
- **Jupyter Notebook**: For interactive exploration and visualizations.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: To build and evaluate machine learning models.
- **Matplotlib/Seaborn**: For data visualization.
- **NumPy**: For numerical operations.
  
## Machine Learning Models
### Logistic Regression
- **Accuracy**: 74%
- **Confusion Matrix**:
  ```bash
  [[120  30]
   [ 25  95]]
### Decision Tree
- **Accuracy**: 72%
- **Confusion Matrix**:
  ```bash
  [[115  35]
   [ 28  92]]

## Feature Importance (Decision Tree):
The following features were identified as the most important in predicting loan approval:
- Loan Amount
- Credit History
- Applicant Income

## Model Development
- Data Preprocessing: Handled missing values, performed data cleaning, and feature engineering.
- Feature Selection: Used correlation analysis and feature importance methods to select key features.
- Model Training: Trained models using Logistic Regression and Decision Tree classifiers.
- Evaluation: Evaluated models using metrics like Accuracy, Precision, Recall, and Confusion Matrix.
 
## Results
The Logistic Regression model performed slightly better than the Decision Tree in terms of accuracy (74% vs. 72%). However, the Decision Tree provided better insight into the key features that influence loan approval decisions, such as Loan Amount and Credit History.

## Future Enhancements
- Add more advanced algorithms like Random Forest and XGBoost to improve model accuracy.
- Integrate deep learning models using TensorFlow or PyTorch for better predictions.
- Incorporate additional features like Credit Score, Loan Repayment History, and Debt-to-Income Ratio.

## Conclusion
This project demonstrates the potential of machine learning models to improve decision-making in the financial sector, particularly for credit risk assessment. The insights generated from the model can help financial institutions make more informed lending decisions and reduce default risks.

To access the file click here: https://lakshdugar.github.io/CreditRiskLoanPrediction/CreditRiskData.html
