# Customer Churn Prediction

## Overview
This project focuses on predicting customer churn using IBM SPSS Modeler. The primary objective is to identify telecom customers who are most likely to discontinue services, enabling proactive retention strategies.

## Objectives
- Build and evaluate a predictive churn model.
- Perform data cleaning, filtering, and feature definition.
- Apply the trained model to deployment data for real-world predictions.

## Tools & Technologies
- **IBM SPSS Modeler** – Data preprocessing, modeling, and prediction.
- **Microsoft Excel** – Data import/export.
- **Flat File Export** – Result storage and reporting.

## Methodology
1. **Data Import:** Load telecom dataset via the Excel Node in SPSS Modeler.  
2. **Filtering:** Use the Select Node to retain valid records (`data_known = "yes"`).  
3. **Field Definition:** Configure data types and set `churn` as the target field using the Type Node.  
4. **Modeling:** Apply the Churn Node to train and generate the churn model.  
5. **Prediction:** Run the model to obtain fields like `$R-churn` and `$RC-churn`.  
6. **Deployment:** Import new data, apply the trained model, and identify likely churners (`$RC-churn > 0.94`).  
7. **Export:** Filter essential fields and export final results using a Flat File Node.

## Results
- Successfully built and tested a churn prediction model.
- Identified customers with a high probability of churn.
- Generated an exportable report for business analysis.

## Project Details
**Institution:** Babu Banarasi Das University  
**Course:** Predictive Analytics (BCADSN15301)  
**Submitted By:** Varsha Tiwari (Roll No: 1230258467)  
**Submitted To:** Mr. Ayushman  
**Class:** BCADS-36

## Conclusion
The project effectively demonstrates the use of predictive analytics for customer churn identification, offering actionable insights to improve customer retention and business performance.
