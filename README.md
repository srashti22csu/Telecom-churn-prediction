# Customer Churn Prediction

## Overview

Customer Churn Prediction is a machine learning project designed to identify customers who are likely to stop using a company's services. By analyzing customer behavior, demographics, and service usage patterns, the model helps businesses proactively retain customers and reduce revenue loss.

## Problem Statement

Customer acquisition is often more expensive than customer retention. The objective of this project is to predict whether a customer will churn based on historical customer data and usage patterns, enabling businesses to implement targeted retention strategies.

## Dataset

The project uses customer information containing features such as:

* Customer demographics
* Subscription details
* Tenure with the company
* Monthly and total charges
* Internet and phone services
* Contract type
* Payment method
* Customer support interactions

### Target Variable

* **Churn**

  * `Yes` → Customer is likely to leave.
  * `No` → Customer is likely to stay.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* XGBoost
* SHAP
* Jupyter Notebook

## Project Workflow

### 1. Data Collection

Collected and loaded customer data for analysis and model training.

### 2. Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature scaling and normalization
* Outlier detection and treatment

### 3. Exploratory Data Analysis (EDA)

Performed detailed analysis to understand:

* Churn distribution
* Feature correlations
* Customer behavior patterns
* Key factors affecting churn

### 4. Feature Engineering

Created meaningful features to improve model performance and predictive capability.

### 5. Model Development

Multiple machine learning models were evaluated, including:

* Logistic Regression
* Random Forest
* XGBoost

XGBoost was selected as the final model due to its superior performance and robustness.

### 6. Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

### 7. Model Explainability

SHAP (SHapley Additive exPlanations) was used to explain model predictions and identify the most influential factors contributing to customer churn.

## Key Insights

Some major factors influencing churn include:

* Contract type
* Monthly charges
* Customer tenure
* Payment method
* Internet service type

## Business Impact

The solution enables businesses to:

* Identify high-risk customers early.
* Improve customer retention strategies.
* Reduce customer acquisition costs.
* Increase customer lifetime value.

## Future Improvements

* Real-time churn prediction API deployment.
* Integration with CRM systems.
* Automated retention campaign recommendations.
* Deep learning-based predictive models.

## Project Structure

```text
customer-churn-prediction/
│
├── data/
├── notebooks/
├── models/
├── src/
├── requirements.txt
├── churn_model.pkl
├── README.md
└── app.py
```

## Conclusion

This project demonstrates how machine learning can be leveraged to predict customer churn and support data-driven business decisions. By identifying customers at risk of leaving, organizations can take proactive actions to improve customer satisfaction and retention.
