# credit-risk-classification

Analysis Overview:

Purpose: The purpose of the analysis was to develop machine learning models to predict the risk level of loans based on financial information.
Financial Information: The data included various financial features such as credit score, income, debt-to-income ratio, loan amount, etc. The target variable was the loan status, indicating whether a loan is healthy (0) or high-risk (1).
Target Variable (Loan Status):
Healthy (0): Indicates a healthy loan.
High-risk (1): Indicates a high-risk loan.
Machine Learning Process:
Feature Engineering: Feature selection or extraction techniques were applied to identify relevant features for model training.
Model Training: The selected model was trained using the training data.
Model Evaluation: The trained model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score on the testing data.
Methods Used:
Logistic Regression: Used for binary classification tasks like predicting loan status.

Machine Learning Model: Logistic Regression


Accuracy, Precision, and Recall Scores:
Accuracy: The proportion of correctly classified instances out of the total instances.
Precision: The proportion of true positive predictions out of all positive predictions made by the model.
Recall: The proportion of true positive predictions out of all actual positive instances in the dataset.


Accuracy:
99%

Precision:
Class 0 (Healthy loans): 100%
Class 1 (High-risk loans): 86%
Recall:
Class 0 (Healthy loans): 100%
Class 1 (High-risk loans): 91%

Summary:
Based on the results, I recommend utilizing the machine learning model for the following reasons:

High Accuracy: With an accuracy score of 99%, the model demonstrates good overall performance in predicting the outcome.
Balanced Precision and Recall: The model achieves a balance between precision and recall, with both scores above 85%. This indicates that the model not only makes accurate predictions but also captures a significant portion of positive instances.
Generalizability: The model's performance suggests that it can generalize well to unseen data, making it potentially useful for future predictions.
Applicability to Business Needs: Considering the context of the company's objectives and requirements, the model's performance aligns with the desired outcomes and can provide valuable insights for decision-making.
It's essential to consider the trade-offs between precision and recall depending on the business requirements. For example, in the context of loan risk assessment, false positives (predicting a loan as high-risk when it's actually healthy) might lead to missed opportunities, while false negatives (predicting a loan as healthy when it's high-risk) could lead to increased financial risk for the lender. Therefore, the choice of the best model should consider the balance between these factors.