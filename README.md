# Customer Churn Prediction

Machine learning model predicting which telecom customers are likely to churn,
paired with a churn-risk dashboard for business use.

## Business Question
Which customers are at the highest risk of churning, and which factors (contract type,
tenure, charges) drive that risk?

## Dataset
[Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
— 7,043 customer records with account, service, and demographic details.

## Tools
Python (Pandas, Scikit-learn), Seaborn/Matplotlib, Google Colab, Power BI

## Workflow
1. **Cleaning** — fixed TotalCharges data type, handled nulls, dropped identifier column
2. **EDA** — churn distribution by tenure, contract type, and monthly charges
3. **Feature Engineering** — one-hot encoded categorical variables
4. **Modeling** — Logistic Regression baseline with train/test split and scaling
5. **Evaluation** — classification report, ROC-AUC, confusion matrix, feature importance
6. **Visualization** — exported predictions to Power BI for a churn-risk dashboard

## Model Performance
*(fill in your actual results)*
- ROC-AUC: X.XX
- Precision/Recall: see classification report in notebook

## Key Findings
*(fill in after running)*
- e.g. Month-to-month contracts show significantly higher churn than annual contracts
- Tenure is one of the strongest negative predictors of churn
- [Feature] is the top driver of churn risk per the model coefficients

## Repo Structure
