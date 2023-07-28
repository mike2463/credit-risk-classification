# credit-risk-classification

## Analysis

The purpose of this analysis is to predict the credit worthiness of potential borrowers. By looking at their income, age, derogatory marks, loan status, the logistic model can predict with 99% accuracy a person's credit worthiness. In order to make this prediction I split the data into X and y variables, where X held all the financial and demographic information and y held the loan status. In the process of doing the prediction I looked at how many of the loans are considered healthy loans (0) and how many are considered high-risk loans (1). There are 75,036 healthy loans and 2,500 high-risk loans. 

In order to train the model, I split the X and y into train and test. I created the logistic model and then fit the training data to the model and then had the model make predictions based on the X_train data. Then, I calculated the accuracy score by comparing the predictions to the y_test data where I got 18,663 true negatives, 102 false positives, 56 false negatives, and 563 true positives. For an accuracy score of 99%. 

* Machine Leering Model 1
  * Accuracy Score: 99%
  * Precision Scores: 0: 100%, 1: 85%
  * Recall Scores: 0: 99%, 1: 91%

* Machine Learning Model 2
  * Accuracy Score: 99%
  * Precision Score: 0: 100%, 1: 84% 
  * Recall Scores: 0: 99%, 1: 99%

Both models performed very well. They both had an accuracy score of 99%, precision scores of healthy loans of 100%, and recall scores of healthy loans of 99%. Where the second model performed overall a little better is in the prediction of the high-risk loans. Though the first model performed 1% better in the precision scores, the second model performed 8% better in the recall scores. The 8% better performance would lead me to use the second model. When predicting healthy loans and high-risk loans, it is equally important to look at both. As it is a financial institutions goal to make money from the loans, they want to make sure that they are giving out as many healthy loans as they can so they would want to be able to accurately predict the potential for a healthy loan. At the same time, they would want to be able to predict a high-risk loan in order to prevent giving out a loan that will default or be able to charge a much interest rate because it is a high-risk loan. Either way it is important to be able to make these predictions accurately. Using the logistic model is going to be able to best predict the credit worthiness of a person because it is designed to predict the probability of event occurring. In this case the event occurring would be whether a loan is healthy or not. 

