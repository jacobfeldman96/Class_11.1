# Class 11.1

November 21, 2020

The class began with a recap of various components of linear regressive predictive models. We discussed the utility of P values for stationary or non stationary data sets, ARMA and ARIMA's major KPI for predictive success, AIC and BIC, GARCH being a volatility prediction model, Linear Regression, and Multiple Regression. Mia also gave clarification on R2 and RMSE. R2 is a correlation coefficient that describes the suitability of the model's predictive power, the higher the better. RMSE should be lower than the std of the dependent variable for greatest predictive success. 

Mia further discussed R2's limits for accuracy. If there is no randomness present in residual graph, the model is not good and either needs fine tuning or more data. Furthermore, In-sample and out-of-sample RMSE should be within 25% of each other in order to be predictive. 

## Classical Classification

Classification is a part of supervised learning and works with labeled data. Classification is used for image classification, Identity Fraud Detection, Customer Retention and Diagnostics. 

Classification is the prediction of discrete, or single, outcomes. Outcomes are identified as labels, which serve to categorize bi-class and multi-class features. Classification is used to forecast and predict financial outcomes. 

### Logistic Regression Model

As opposed to the three steps in linear regression predictive models, there are four steps in logistic regression models. They are: preprocess, train, validate and predict. 

There are four metrics for judging the effectiveness of the prediction and they are: accuracy, precision, recall and F1. The possible outcomes of a these predictive tests are True Postives, False Positives, False Negatives and True Negatives to show how well the algorithm has performed. The confusion matrix places the predictions into an array of TP, FP, FN, TN. An innacurate and imprecise model will return false positives and not false negatives. 

Accuracy can be calculated by (TP + TN)/(TP + TN + FP + FN). 

Precision can be calculated by TP/(TP + FP).

Recall can be calculated by TP/(TP + FN). In healthcare it is vital to have as low a recall number as possible. 

Problems will arise with imbalanced data sets and as a result one, needs a metric that is more suitable than recall and precision and that is F1. F1 will identify the extreme cases. 

F = 2(precision * recall)/(precision + recall).

If all the scores return accurate measures more than 80% of the time, the algorithm is ready for use. If it is positive but still underperforming, the model may simply require more data to learn form. 