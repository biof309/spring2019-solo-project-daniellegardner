=========
Blood Donation Prediction
=========

In this project, I analyze data on donation characteristics of blood donors and predict whether a donation will be made in the present month

`View notebook on nbviewer <https://nbviewer.jupyter.org/github/biof309/spring2019-solo-project-daniellegardner/blob/master/blood_donation_prediction.ipynb>`_

`View presentation <http://spring2019-solo-project-daniellegardner.s3-website-us-east-1.amazonaws.com/>`_

Description
===========

Data on donation characteristic of blood donors -- including months since last donation, total number of donations and volume donated, and time since first donation -- are analyzed and visualized using pandas, matplotlib, and seaborn. Data are fit to machine learning models for classification, to predict whether or not a donation will be made in the present month. Tested models, from scikit-learn, include a support vector classifier, logistic regression, and K nearest neighbors model. Models are optimized using grid search and assessed by accuracy and ROC AUC score. A deep learning model in keras is tested as well. Highest accuracy, achieved with K nearest neighbors model, is 79%.

Data source: Yeh, I-Cheng, Yang, King-Jang, and Ting, Tao-Ming, "Knowledge discovery on RFM model using Bernoulli sequence," Expert Systems with Applications, 2008. Accessed from UCI Machine Learning Repository.

Note
====

This project has been set up using PyScaffold 3.1. For details and usage
information on PyScaffold see https://pyscaffold.org/.
