Here's a concise GitHub README file based on the details provided:

---

# Lauki Finance: Credit Risk Modelling App

## Overview
Lauki Finance is a **Streamlit-based machine learning application** designed for **credit risk modeling**. The app predicts the **probability of loan default** and assigns credit ratings using a Logistic Regression model. It is optimized for high accuracy and reliable predictions in financial risk analysis.

## Final Model Performance
The final model, **Logistic Regression**, demonstrated strong performance on the test dataset:

- **Precision (Class 1 - Default):** 57%  
- **Recall (Class 1 - Default):** 94%  
- **F1-Score (Class 1 - Default):** 71%  
- **Overall Accuracy:** 93%  
- **Support:** 12,497 samples

The model prioritizes recall to minimize missed default predictions while maintaining high overall accuracy.

## Key Features
- Predicts **probability of default (PD)** for loan applicants.
- Provides a **credit rating** based on the applicant's risk profile.
- Displays **feature importance** for interpretability.

## Dataset
The dataset includes financial and demographic variables such as:
- Loan-to-income ratio
- Credit utilization ratio
- Delinquency ratio
- Number of open accounts
- Loan purpose and tenure


## Future Enhancements
- Integrate additional ML models (e.g., XGBoost) for comparison.
- Add more user-friendly visualizations for credit insights.
- Explore hyperparameter tuning for further optimization.

---
