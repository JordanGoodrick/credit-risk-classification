# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge.

* Explain the purpose of the analysis.
* This analysis will cover the accuracy of a data model that was used to predict the credit-worthiness of potential lenders. Ideally, we are predicting whether or not a loan would be considered high-risk or healthy given factors like the loan size, interest rate and the borrowers income in order to minimize the risk of rejecting borrowers that could handle the loan or accepting borrowers who couldn't. To make this possible, I used pandas for my data frames and Sk.Learn's logistic regression algorithm.


After running a classification report my machine learning model, I recieved the following outputs:
    Weighted accuracy of .99
    Precision of 1.00 for healthy loans, and .84 for high-risk loans. 
    Recall of .99 for healthy loans, and .94 for risky ones. 


## Summary

Summarize the results of the machine learning model:

The model has a high level of accuracy, but is ultimately more accurate at positively identifying healthy loans. As it has a high level of accuracy when predicting healthy loans, I would use it to ensure that rejections stay low, allowing for more loans to be given. 


