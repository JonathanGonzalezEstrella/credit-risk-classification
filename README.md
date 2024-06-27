# credit-risk-classification
# Credit Risk Classification

## Overview
The purpose of this analysis is to develop a logistic regression model that can predict the creditworthiness of borrowers based on historical lending data from a peer-to-peer lending services company. By identifying high-risk loans, the company can make informed decisions and reduce financial losses. This analysis involves splitting the data into training and testing sets, creating a logistic regression model, evaluating its performance, and summarizing the findings.

## Results
- **Accuracy Score**: 0.99
- **Precision Score**: 
  - Healthy Loans (0): 1.00
  - High-Risk Loans (1): 0.86
- **Recall Score**:
  - Healthy Loans (0): 1.00
  - High-Risk Loans (1): 0.91

## Summary
The logistic regression model demonstrates excellent performance in predicting healthy loans with perfect precision and recall. It also performs very well in predicting high-risk loans, with high precision and recall, although there is some room for improvement in reducing false positives. 

### Detailed Performance Metrics:
- **Confusion Matrix**:
- - True Positives (Healthy Loans correctly identified): 14,926
- False Positives (Healthy Loans incorrectly identified as high-risk): 75
- False Negatives (High-risk loans incorrectly identified as healthy): 46
- True Negatives (High-risk loans correctly identified): 461

- **Classification Report**:
-        precision    recall  f1-score   support

       0       1.00      1.00      1.00     15001
       1       0.86      0.91      0.88       507

accuracy                           0.99     15508

### Conclusion:
Based on these results, the logistic regression model provides reliable predictions for identifying the creditworthiness of borrowers. It achieves high accuracy, precision, and recall, making it suitable for use by the company to distinguish between healthy and high-risk loans. The model's high performance in predicting healthy loans ensures minimal financial risk, while its good performance in identifying high-risk loans helps in proactive decision-making to mitigate potential losses.
