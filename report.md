## Overview of the Analysis

In this assignment, we built a Logistic Regression model to decide if a future loan is considered healthy or high risk.
We train and test our model using previous loan records.
The model will predict the 'loan_status' column which is healthy is represent by 0 and 1 for high risk.
The model will using the remaining loan info such as the loan size, interest rate, customer 's income and debt to predict the loan status.
Our data came from a csv file, where the 'loan_status' column is the label and the others are the features.
Then we assign 75% of the data to train the model, and the remaining 25% for testing.
The model was trained using LogisticRegression from the Sklearn library.

## Results

Overall we have a very solid model with high accuracy, precision, and recall scores.

* Accuracy: 0.99

Healthy:
* Precision: 1.00
* Recall: 1.00

High-Risk:
* Precision: 0.87
* Recall: 0.89

## Summary

I believe our model is relatively trust worthy. It does really well on predicting healthy loan with a f1-score very close to 1(We can see from the confusion matrix that the f1-score is not a perfect 1). On predicting high-risk loan, it does not do as well but it is still a good f1-score (88%). It is a model I would recommend.
