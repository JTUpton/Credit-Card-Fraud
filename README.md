# Credit-Card-Fraud

In this project several models are trained and evaluated in terms of how effectively they predict instances of fraud using data based on a dataset from Kaggle.   

Features include confidential variables V1 through V28 as well as Amount which is the amount of the transaction. 
The target is stored in the class column, where a value of 1 corresponds to an instance of fraud and 0 corresponds to an instance of not fraud.

Logistic Regression Classifier and SVC classifier with default parameters are trained and evaluated for accuracy, recall, and precision.

A grid search is performed to determine the best combination of parameters for Logistic Regression Classifier as evaluted 
by recall scores on the test set.
