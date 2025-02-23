# Credit-Risk-Classification
The purpose of this analysis is to train a model that will allow us to analyze the loan risk for both healthy and high-risk loans. 
The data that was provided were based on things about the loan and the loanee. 
For example, it included things like how much the loan is, what the interest rate is, the loanee’s income, and how much debt the loanee is in. 
The target variable that we are trying to predict is the loan status and some basic information about this column would be that out of the 77,536 loan applications in the data set,
only 2,500 applications are considered as high-risk loans. The first step in creating the logistic regression model is that we had to fit the model using training data. 
We then had to create predictions on the testing data using X_test and the fitted model. Finally, we evaluated the model’s performance and analyzed our findings. 

The Results:
•	The accuracy score given for our model was 0.99, meaning that it was very accurate
•	The precision score for our model was 1 and 0.86 (weighted avg of 0.99) for healthy and high-risk loans meaning that there is not a lot of false positives and it’s predictions are correct
•	The recall score for our model was 0.99 and 0.94 for healthy and high-risk loans. This means that our model did a good job at predicting true positives and had minimal false negatives.
 Summary
Our logistical regression model was very accurate in predicting the loan status for healthy and high-risk loans with the weighted average being 0.99 for all of precision, recall and the f1-score. 
This means that a logistical regression model was good to use for the data that we have. The performance does, however, depend on what we are trying to solve. 
If we were to try to maximize the high-risk loans, the model performance would be a little less accurate in all of the categories of precision, recall, and f1-score. 
These scores, however, should be acceptable with the lowest being precision with a 0.86 as the score. 
