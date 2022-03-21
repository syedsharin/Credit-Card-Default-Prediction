# Credit-Card-Default-Prediction
Problem Description

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments

Objective:

Objective of our project is to predict which customer might default in upcoming months. Before going any fudther let's have a quick look on defination of what actually meant by Credit Card Default.

We are all aware what is credit card. It is type of payment payment card in which charges are made against a line of credit instead of the account holder's cash deposits. When someone uses a credit card to make a purchase, that person's account accrues a balance that must be paid off each month.

Credit card default happens when you have become severely delinquent on your credit card payments.Missing credit card payments once or twice does not count as a default. A payment default occurs when you fail to pay the Minimum Amount Due on the credit card for a few consecutive months.

Conclusion:

This project provides a performance evaluation of credit card default prediction. Thus different models are used to test the variable in predicting the credit default and we found Random Forest Classifier performs the best with a recall of 0.95 on the test set. Followed by RFC we observed that Gradient Boosting and XGBoost performed the best with test recall score of 0.93 and 0.92 respectively. We could overcome the overfitting of multi models by using hyperparameter tuning and cross validation, which is evident by comparing the scores before and after. Model explainability was performed on the Random Forest Classifier using Lime and ELI5, Repayments columns (especially the latest months) has the most significant impact on whether a customer is a Defaulter or Not.
