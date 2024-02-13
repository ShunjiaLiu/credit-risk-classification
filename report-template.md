# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis was to evaluate machine learning models for predicting loan health based on financial information. The dataset contained features related to loans, and the goal was to predict whether a loan is healthy (0) or high-risk (1).

* Explain what financial information the data was on, and what you needed to predict.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

* Describe the stages of the machine learning process you went through as part of this analysis.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.


Overview of the Analysis:

The purpose of this analysis was to evaluate machine learning models for predicting loan health based on financial information. The dataset contained features related to loans, and the goal was to predict whether a loan is healthy (0) or high-risk (1).

Variables to Predict (value_counts):

Healthy Loans (0): 18,765 instances
High-risk Loans (1): 619 instances


Stages of the Machine Learning Process:

Data Exploration: Explored the dataset to understand its structure, features, and class distribution.
Data Preprocessing: Handled missing values, encoded categorical variables, and scaled numerical features.
Model Selection: Chose machine learning models suitable for binary classification tasks, such as Logistic Regression and potentially others.
Model Training: Trained models on the dataset, considering class imbalance.
Model Evaluation: Evaluated models using metrics like accuracy, precision, recall, and F1-score.
Resampling: Addressed class imbalance using oversampling methods to enhance model performance.
Results:

Machine Learning Model 1: Logistic Regression with Oversampling

.Balanced Accuracy: High
.Precision for 0 (Healthy Loan): 1.00
.Precision for 1 (High-risk Loan): 0.84
.Recall for 0: 0.99
.Recall for 1: 0.99
.For class 0, the F1-score is 1.00
.For class 1, the F1-score is 0.88

Machine Learning Model 2: (if applicable)

.Precision for class 0 (healthy loan) is 1.00,  
.Precision for class 1 (high-risk loan) is 0.84
.For class 0, the F1-score is 1.00
.For class 1, the F1-score is 0.91
.Recall for class 0 is 0.99
.Recall for class 1 is 0.99




## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


Precision for class 0 (healthy loan) is 1.00,  meaning 100% of the time. Precision for class 1 (high-risk loan) is 0.84, meaning correct about 84% of the time. For class 0, the F1-score is 1.00, and for class 1, it is 0.91. The weighted average of these scores is 0.99. Recall for class 0 is 0.99, suggesting that the model correctly identifies about 99% of the actual healthy loans.
Recall for class 1 is 0.99, indicating that the model captures about 99% of the actual high-risk loans. F1-score considering both precision and recall, indicates that oversampling helps improve the classification performance, especially in the recall aspect. 
