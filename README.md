# Bank Customer Churn Prediction Using CHAID Decision Tree in IBM SPSS Modeler

## Overview
This project predicts bank customer churn using the CHAID (Chi-squared Automatic Interaction Detection) decision tree algorithm in IBM SPSS Modeler. It analyzes customer demographics, tenure, and financial behavior to identify key drivers of churn and assist banks in developing effective customer retention strategies.

## Problem Statement
Financial institutions worldwide face an average customer churn rate of 17.6% in 2025, resulting in an estimated $195 billion loss for U.S. banks annually. While acquiring a new customer costs around $390, retaining one costs only $75.  
This project leverages data analytics and predictive modeling to detect at-risk customers early, identify the main factors influencing churn, and support strategic decision-making to improve customer loyalty.

## Objective
To build and evaluate a CHAID decision tree model that:
- Classifies customers as likely to churn or stay.
- Identifies key churn predictors.
- Provides interpretable decision rules for actionable business insights.

## Dataset
**Source:** [Kaggle – Bank Customer Churn Data](https://www.kaggle.com/datasets/pentakrishnakishore/bank-customer-churn-data)

**Key Attributes:**
- Demographics: Age, Gender, Occupation, City  
- Account Tenure: Account vintage (years)  
- Financial Data: Balance, Net Worth, Credit Score  
- Behavioral Data: Monthly transactions, Product usage  
- Target: Churn (Yes/No)

## Tools and Technologies
- IBM SPSS Modeler – for data modeling and visualization  
- CHAID Algorithm – for decision tree-based classification  
- Kaggle Dataset – real-world banking churn data  
- MS Excel / CSV – for data preprocessing

## Methodology
1. **Data Import:** Loaded dataset into IBM SPSS Modeler and verified column integrity.  
2. **Data Preparation:** Cleaned and standardized data, handled missing values.  
3. **Variable Assignment:** Defined churn as the target variable and assigned predictor roles.  
4. **Model Configuration:** Set CHAID parameters including significance level and maximum tree depth.  
5. **Model Execution:** Trained the CHAID model and generated decision tree outputs.  
6. **Result Interpretation:** Analyzed node splits and extracted churn-related business rules.

## Results
- Key churn predictors: Account tenure, balance, transaction frequency, and age.  
- CHAID model provided interpretable segmentation with clear decision rules.  
- Findings enable targeted retention actions and reduced attrition costs.

## Conclusion
The CHAID decision tree effectively identifies customer segments with higher churn likelihood. By applying this model, banks can proactively implement retention strategies, reduce acquisition costs, and improve overall profitability through data-driven insights.

## Future Work
- Compare CHAID performance with advanced algorithms (Random Forest, XGBoost).  
- Integrate results into a real-time churn prediction dashboard.  
- Include sentiment analysis and behavioral data for improved model accuracy.  
- Automate retention campaign recommendations.

## Project Structure
```
bank-customer-churn-prediction-chaid-spss/
│
├── bank_customer_churn.pdf          # Detailed workflow and results
├── PROBLEM STATEMENT.pdf            # Problem background
├── dataset.csv                      # Input dataset (from Kaggle)
├── stream                           # IBM SPSS Modeler stream (CHAID model workflow)
└── README.md                        # Project documentation
```

## Author
**Akbar Naeem**  
*Babu Banarasi Das University*  
*Supervisor: Mr. Vikas Kumar*
