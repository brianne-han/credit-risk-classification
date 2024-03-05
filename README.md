# credit-risk-classification

# Credit Risk Analysis Report

## Overview 
This analysis aims to employ different methodologies for training and assessing a model focused on loan risk. Additionally, machine learning will be utilized to examine a dataset containing past lending activities from a peer-to-peer lending services provider, to construct a model capable of discerning the creditworthiness of borrowers. Two machine learning models were used: one with the original data, and one with the resampled training data. 

-----

## Results
### Model 1
* Accuracy Score: The accuracy score is 0.99, meaning the model performed exceptionally well.
* Precision Score: For the "healthy loan", the precision score is 1.00 which means that the model predicts this label with perfect precision. For the "high-risk loan", the precision score is 0.87, meaning that 87% of the predicted high-risk loans are correct.
* Recall Score: The recall for the "healthy loan" is 1.00, indicating that the model captures all the actual healthy loans. The recall for the "high-risk loan" is 0.89, meaning that the model identifies 89% of the high-risk loans correctly.

### Model 2
* Accuracy Score: The accuracy score is 1.00, meaning the model performed exceptionally well.
* Precision Score: For the "healthy loan", the precision is 1.00, indicating that the model predicts this label with perfect precision. For the "high-risk loan", the precision is 0.87, meaning that 87% of the predicted high-risk loans are correct.
* Recall Score: The recall for both the "healthy loan" and "high-risk loan" is 1.00, indicating that the model captures all the actual healthy and high-risk loans correctly.

-----

## Summary
After examining the results, it was noted that both models demonstrated impressive accuracy, precision, and recall scores. Nevertheless, the logistic regression model that incorporated resampling displayed slightly better performance. The oversampled model demonstrates enhanced capability in accurately detecting instances of the "high-risk loan" category, leading to higher recall and F1-score. 
Given the goal of accurately identifying both healthy and high-risk loans, the logistic regression model with resampling emerges as the preferred option.
