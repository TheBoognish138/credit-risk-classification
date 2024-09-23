# Module 12 Report Template

## Overview of the Analysis

* The purpose of this analysis is to demonstrate supervised machine learning using multiple algorithms.
* The dataset used contains information on the following: loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, loan_status.
* The goal is to predict the outcome which in this case would be the loan_status.
* Algorithms used include: Logistic Regression, Decision Tree, Random Forest, SVC, KNeighbors, Extra Trees, Ada Boost, Gradient Boosting, xgboost, and lightgbm.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression:
    * Positive:
        * Precision: 0.87, Recall: 0.98, Accuracy: 0.99
    * Negative:
        * Precision: 1.00, Recall: 1.00, Accuracy: 0.99 
* Decision Tree:
    * Positive:
        * Precision: 0.87, Recall: 0.81, Accuracy: 0.99
    * Negative:
        * Precision: 0.99, Recall: 1.00, Accuracy: 0.99 
* Random Forest:
    * Positive:
        * Precision: 0.88, Recall: 0.88, Accuracy: 0.99
    * Negative:
        * Precision: 1.00, Recall: 1.00, Accuracy: 0.99
* Support Vector Machine:
    * Positive:
        * Precision: 0.87, Recall: 1.00, Accuracy: 0.99
    * Negative:
        * Precision: 1.00, Recall: 1.00, Accuracy: 0.99
* K Nearest Neighbors (15 neighbors):
    * Positive:
        * Precision: 0.87, Recall: 0.99, Accuracy: 0.99
    * Negative:
        * Precision: 1.00, Recall: 1.00, Accuracy: 0.99
* Extra Trees:
    * Positive:
        * Precision: 0.87, Recall: 0.83, Accuracy: 0.99
    * Negative:
        * Precision: 0.99, Recall: 1.00, Accuracy: 0.99
* Adaboost:
    * Positive:
        * Precision: 0.87, Recall: 0.99, Accuracy: 1.00
    * Negative:
        * Precision: 1.00, Recall: 1.00, Accuracy: 1.00
* Gradient Boosting:
    * Positive:
        * Precision: 0.87, Recall: 0.99, Accuracy: 0.99
    * Negative:
        * Precision: 1.00, Recall: 1.00, Accuracy: 0.99

## Summary

* The Support Vector Machine model appears to work the best. This is because it has the highest recall with the fewest false negatives.
* In this problem the goal is to minimize false negatives.
In the real world I would not reccomend any of the models for this dataset due to the large imbalance.
