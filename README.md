# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to evaluate a model based on loan risk.
* Based on dataset of historical lending activity from peer-to-peer lending services company, we can identify the creditworthiness of borrowers.
* As part of this analysis, following has been performed:
	- uploading css file from the Resources folder;
	- separating data into labels and features;
	- X variables in DataFrame: loan size, interest rate, borrower's income, debt to income ratio, Toal amount of debt;
	- data split using train_test_split;
	- fit logistic regression model by using the training data;
	- make and save the predictions;
	- evaluation of model's performance by generating confusion matrix and classification report.

## Results

- Precision for healthy loans is 1, which is perfect. Precision for high rist loans is .85, which means 85% of the predicted high risk loans is correct.
- Recall for healthy loans is .99 and .91 for unhealthy loans. Which means that the model captures the actual instances with pretty high accuracy. 
- F1-score is 1 for healthy loans. For high risk loans it is .88, which represents a good balance between precision and recall for this label. 
- The model performed with 99% accuracy. 
- Suggestion would be to work on lowering "False Negative" value of 56 for high risk loans. Which would allow to identify positive instances.
