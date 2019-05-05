=========
Blood Donation Prediction
=========

In this project, I analyze data on donation characteristics of blood donors and predict whether a donation will be made in the present month

`View notebook on nbviewer <https://nbviewer.jupyter.org/github/biof309/spring2019-solo-project-daniellegardner/blob/master/blood_donation_prediction.ipynb>`_.

Description
===========

Data on donation characteristic of blood donors -- including months since last donation, total number of donations and volume donated, and time since first donation -- are analyzed and visualized using pandas, matplotlib, and seaborn. Data fit to ML models for classification, to predict whether or not a donation will be made in the present month and probability of donation. Tested models, from scikit-learn, include a support vector classifier, logistic regression, and K nearest neighbors. Models are optimized using grid search and assessed by accuracy and ROC AUC score. Deep learning model in keras is tested as well. Highest accuracy, achieved by K nearest neighbors model, is 79%.

Data source: Yeh, I-Cheng, Yang, King-Jang, and Ting, Tao-Ming, "Knowledge discovery on RFM model using Bernoulli sequence," Expert Systems with Applications, 2008. Accessed from UCI Machine Learning Repository.

Note
====

This project has been set up using PyScaffold 3.1. For details and usage
information on PyScaffold see https://pyscaffold.org/.
