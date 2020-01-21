# Predicting-Success-of-Bank-Telemarketing

## Abstract: 
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y)

# About the Problem:
We are given the data of direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (target variable y). This case study is inspired by [this](https://github.com/sukanta-27/Predicting-Success-of-Bank-Telemarketing/blob/master/Relevent%20Paper/targeted_marketing.pdf) research paper where the researchers have used a very similar dataset as the one we will be using throughout this case study for determining the success of Bank Telemarketing. The researchers in their paper have mentioned that the best result they have got was a AUC score of 0.8 and a ALIFT of 0.7. So as a goal we will try to produce a similar result in our case study.

# About the Dataset:
As mentioned above, the dataset consists of direct marketing campaigns data of a banking institution. The dataset was picked from UCI Machine Learning Repository which is an amazing source for publicly available datasets. There were four variants of the datasets out of which we chose “ bank-additional-full.csv” which consists of 41188 data points with 20 independent variables out of which 10 are numeric features and 10 are categorical features.

# Type of Machine Learning problem:
As you would have probably guess it by now, this is a binary classification problem. Our two classes are “yes” denoting that the customer subscribed to a term deposit, and “no” denoting that the customer did not subscribe.

# Performance Metric Used:
The performance metric used for this case study is AUC ROC score also known as AUROC (Area Under the Receiver Operating Characteristics).

# Blog explaning my approach:
https://towardsdatascience.com/machine-learning-case-study-a-data-driven-approach-to-predict-the-success-of-bank-telemarketing-20e37d46c31c

