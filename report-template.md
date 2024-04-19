# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

  In the credit risk classification challenge I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
  The dataset included 77,535 lines of data and was devided into training and testing sets. Logistic Regression Model 1 was built based on the training set, utilizing the LogisticRegression module of scikit-learn. The model was then used for the testing data as well. The purpose of the model was to identify whether a loan to the borrower in the test data would be of a high or a low risk.
  Dataset included the below attributes:
  - Loan size
  - Interest rate
  - Borrower income
  - Debt to income
  - Number of accounts
  - Derogatory marks
  - Amount of total debt
  - Loan status

  The goal of this challenge was to try to predict status of loan, whether it's 0 or 1, where 0 means low-risk or helathy loan and 1 stands for a high risk loan. The first set of variables include the majority of values and counts up to 75036 of healthy loan. The second set of variables counted 2500 of high risk loan.

  Major steps of the Machine Learning model are laid out below:
  1. Split the Data into Training and Testing Sets
  2. Create a Logistic Regression Model with the Original Data
  3. Evaluate the model’s performance by doing the following:
  - Generate a confusion matrix
  - Print the classification report
    

## Results
 
  Below are primary results of the Logistic Regression Model:

  Counting variable we've found out that the dataset is frankly imbalanced, as around 97% of data represents heealthy loans. The model predicted a healthy loan with 100% of precision, whereas a high-risk loan is at precision level of 84%. The balanced accuracy of the model is 99%.

  The model indicates a recall score of 99% for the low-risk loans and 94% for the high-risk loans. The scores imply that for all the instances where the loans were actually healthy, 99% of the times they were classified correctly. F1-score of healthy loans indicates absolute reliability of the data with a value of 1 = 100%, when the same metric for high-risk loans shows lower score of 89%.



