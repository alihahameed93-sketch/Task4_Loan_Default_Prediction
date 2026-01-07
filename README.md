# Loan Default Prediction with Business Cost Optimization

## Overview
This project focuses on predicting loan defaults for a bank using historical
credit data. Incorrect lending decisions can result in significant financial
losses, so the model also optimizes the decision threshold based on business costs.

## Dataset
- **Source:** German Credit Data
- **Columns:** ['status', 'duration', 'credit_history', 'purpose', 'amount', 'savings',
                'employment_duration', 'installment_rate', 'personal_status_sex',
                'other_debtors', 'present_residence', 'property', 'age',
                'other_installment_plans', 'housing', 'number_credits', 'job',
                'people_liable', 'telephone', 'foreign_worker', 'credit_risk']
- **Target Column:** `credit_risk` (0 = Good credit, 1 = Bad credit)

## Objective
1. Predict whether a customer will default on a loan.
2. Optimize classification threshold to minimize total business cost
   (false positives and false negatives).

## Approach
1. Loaded and explored the dataset.
2. Encoded categorical features using LabelEncoder.
3. Split dataset into training and testing sets (25% test).
4. Standardized numerical features using StandardScaler.
5. Trained a Logistic Regression model.
6. Predicted probabilities and applied threshold optimization using a
   custom business cost function.
7. Visualized the confusion matrix and business cost vs threshold.

## Results
- Optimal Threshold: `<insert your value>`  
- Minimum Business Cost: `<insert your value>`  
- Confusion matrix and plots included in the notebook.

## Skills Gained
- Binary classification
- Feature encoding and scaling
- Business cost-based evaluation
- Risk modeling and threshold optimization
- Data visualization

## Conclusion
In this project, the model predicts loan defaults effectively while minimizing
financial losses by aligning predictions with real-world business objectives.
