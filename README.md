# credit-risk-classification

## Credit Risk Classification

In this assessment, machine learning principles and concepts are utilized to analyze lending activity from a lending services company in order to establish a model that has the abillity to identify the credit stability of its borrowers.

## Analysis
* The Analysis considered the following data points:
- size of a loan
- a loan's interest rate
- income of a borrower
- debt to income ratio
- number of accounts held by a borrower
- total debt calculated 

The dataset, ~ 77K points of data, was split into training and testing sets. The training set was used to build an initial logistic regression model using the `LogisticRegression` module from scikit-learn. The Logistic Regression Model was then applied to the testing dataset. The purpose of the model was to determine whether a loan to the borrower in the testing set would be low- or high-risk.


## Results

Below describes the accuracy scores and the precision and recall scores of the machine learning model.

* Logistic Regression Model :
    * Precision: 93.5% (a rough average for the model predicting low-risk loans, the model was 100% precise and 87% precise in predicting high-risk loans)
    * Accuracy: 94%
    * Recall: 95% (a rough average as the model had 100% recall in predicting low-risk loans, and 89% recall in predicting high-risk loans)

## Summary

