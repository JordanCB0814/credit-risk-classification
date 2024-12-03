# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The goal for the analysis was to determine if a Logistic Regression model could be accurate in predicting healthy loans against high risk loans, using an original data set versus a sampled data set.

* Explain what financial information the data was on, and what you needed to predict.
loan_status is the predict value

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
original
value_counts
0       75036
1       2500

oversampled
0       56271
1       56271

* Describe the stages of the machine learning process you went through as part of this analysis.
1. prepared data
2. Separate the data to feature columns where X and Y are the outcome
3. train_test_split
4. Pick the ml model for classification for LogisticRegression
5. Fit the model with trained data
6. Use the model to make predicitons
7. Finally evaluate the predictions comparing metics, confusion matrix, and classification report

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
SKLearn LogisticRegression
train_test_split
confusion_matrix
classification report

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 
    Accuracy: 0.99
    Precision Class 0: 1.00, Class 1: 0.85
    Recall scores Class1: 0.99,  Class2: 0.95

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
Logistic Regression model seemed to perform well especially with prediciting the outcome of healthy loand for class 0. Both recall and precision were high scored

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Yes it would depend upon what specific values you are wanting to acess primarily

If you do not recommend any of the models, please justify your reasoning.
