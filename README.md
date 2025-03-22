# Credit Risk Analysis

## Overview of the Analysis

The purpose of the analysis is to build a model that can identify the creditworthiness of borrowers.
The analysis is essential for ensuring that the logistic regression model is effective in its role of predicting loan risk, ultimately aiding in better financial decision-making and risk management. 
The data pertains to financial information related to loan applicants and their credit risk assessment.
The primary objective of the analysis is to predict the credit risk associated with each loan application.

The stages of the machine learning process of this analysis included the following:

• Spliting the data into training and testing datasets.
• Create and fit a Logistic Regression Model with the training dataset.
• Make a prediction using the testing dataset.
• Evaluate the model’s performance with a confusion matrix and print a classification report.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Description of Model Accuracy, Precision, and Recall scores

Accuracy:
    • The overall accuracy of the model was 0.99 (99%).
    
Precision:
    • For "healthy loan": Precision is 1.00, meaning that all loans predicted as healthy were indeed healthy.
    • For "high-risk loan": Precision is 0.84, indicating that 84% of the loans predicted as high-risk were actually high-risk.
    
Recall:
    •For "healthy loan": Recall is 0.99, which means that 99% of the actual healthy loans were correctly identified by the model.
    •For "high-risk loan": Recall is 0.94, indicating that 94% of the actual high-risk loans were correctly identified.


## Summary

The model demonstrates excellent performance in predicting healthy loans, achieving perfect precision and recall, which indicates that it is highly reliable for this classification. For high-risk loans, while the model still performs well, there is a slight decrease in precision and recall, suggesting that some high-risk loans may not be identified correctly.

Given the model's outstanding performance in identifying healthy loans and its good performance for high-risk loans, it is recommended to use this model for loan classification tasks. However, it may be beneficial to further refine the model for high-risk loans to improve precision and recall. Overall, the model is suitable for deployment, especially in contexts where accurately identifying healthy loans is critical.