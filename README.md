# customer-churn-prediction

This project builds a **Machine Learning pipeline** to predict customer churn using the **Telco Customer Churn dataset**.  
The goal is to identify customers who are likely to leave (churn) so businesses can take preventive actions.  


## Key Steps in Pipeline
1. **Data Ingestion** – Load dataset (Telco Customer Churn).  
2. **Data Preprocessing** – Handle missing values, encode categorical variables, scale numerical features.  
3. **Feature Engineering** – Create new features (e.g., `AvgChargesPerMonth = TotalCharges / (Tenure+1)`).  
4. **Model Training** – Train Random Forest Classifier.  
5. **Model Evaluation** – Evaluate using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.  
6. **Prediction** – Predict whether a customer will churn (Yes/No).



## Model Performance
- **Accuracy:** ~78%  
- **Precision (Churn):** 0.62  
- **Recall (Churn):** 0.48  
- **F1-score (Churn):** 0.54  

Confusion Matrix: 
[[926 107]
[196 178]]

## Requirements

Main libraries used:

pandas

numpy

scikit-learn

matplotlib

seaborn
