# Diabetes-Vorhersage-APP
Diabetes-Predictiction- with Deployment-Heroku

An innovative AI-tool to predict Flight Price

In this data science machine learning project tutorial, we are going to build an end to end machine learning project and then deploy it via Heroku.

Table Of Contents:

App Link :
https://diabetes-prediction-systems.herokuapp.com/

Business Problem:

Inputs features:-
Pregnancies : You have to input how many number of a female got pregnant, if the user is male, kindly use 0 for that.
Glucose : In this feature you have to fill up your Glucose.
BP ( Blood Pressure ) : The User have to fill BP
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
Approach & Results
I have used the following models,

Decision Trees With Tuning
Random Forest with Extensive Tuning
XGBoost
Catboost
So, I have decided to go with Catboost, because it is more robust, it is less prone to overfitting. The results are below after details about Evaluation.

I have used C-Index for Evaluation of the models, below is the formula for calculating C-Index:-

cindex = concordant + 0.5 x ties / permissible

The c-index measures the discriminatory power of a risk score.
A higher c-index indicates that the model's prediction is in agreement with the actual outcomes of a pair of patients.
Results:- image

Tools Used:

Languages Used: Python

Data Analysis: Pandas - Numpy

Visualization: Matplotlib - Seaborn
Preprocessing Data :Using UTILS Library

Machine learning: Scikit_learn for machine

Web Developement: HTML & CSS- JavaScript

Web Developement Framework :Flask

Deployement : Heroku
