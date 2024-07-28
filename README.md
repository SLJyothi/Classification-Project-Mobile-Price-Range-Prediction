# Classification-Project-Mobile-Price-Range-Prediction

## Problem Overview
1.Mobile Price Range Prediction data is a data set containing information regarding RAM, Camera, Mobile Weight, Price Range of different phones.
2.Using the data given we had to build a model for predicting the price range of a mobile phone.
3.To build a machine learning model, we first perform EDA with various plots for better visualization.
4.And then we split it into a training set and a test set and applied various machine learning algorithms using the training data to train the model. Finally, we evaluated the model's performance on the test data to see how well it predicted sales.

## Steps involved in building a ML Model:

Step 1: Data gathering and Understanding

Step 2: Data preparation

Step 3: Data Cleaning

Step 4: Exploratory data analysis

Step 5: Feature engineering and selection

Step 6: ML Model assumption and checks

Step 7: Data preparation for modelling

Step 8: Model Building

Step 9: Model Validation & Evaluation

Step 10: Predictions & Saving model using pickel library.

## Libraries used in EDA & Machine Learning:

Pandas
Numpy
Matplotib
Seaborn
Plotly
Sklearn
Scipy

## Graphs used for representation:

Bar plot
Pie plot
Box Plot
Grouped bar plot
Donut plot
Heatmap
Pair plot

## ML Models used for training & testing:

Logistic Regression
KNN Classifier
Random Forest Classifier
XG Boost Classifier
Light GBM Classifier
CatBoost Classifier
SVM Classifier

## Insights from EDA impacting business:

Phones which are not having 3G don't have 4G connectivity as well.

Phones which are not having Primary cam don't have front cam as well.

Low price phones mostly fall under Rambin 1GB & very high cost phones fall under rambin of 3GB to 4GB.

Very high cost phones have larger screen area & pixel area as well, resulting in better screen quality.

Very high cost phones have larger battery size & mobile weight is lowest.

## Suggestions provided to increase the Sales:

Adequate amount of ram should be in lower range phones too for stabilized performance of phone which can effect the brand image in a positive way.

There are many phones with no front cam through out all price ranges, atleast it should be present in all very high cost phones.

## ML Model selected for deployment: Logistic Regression

Logistic Regression is a “Supervised machine learning” algorithm that can be used to model the probability of a certain class or event. It is used when the data is linearly separable and the outcome is binary or dichotomous in nature.

Although it is said Logistic regression is used for Binary Classification, it can be extended to solve multiclass classification problems as well.

## Advantages:

Simple and easy to implement: Logistic regression is a relatively simple statistical method that does not require much mathematical or statistical knowledge to use.

Works well with small datasets: Logistic regression can work well with small datasets, which is often the case in many practical applications.

Interpretable results: Logistic regression provides coefficients for each independent variable that can be interpreted as the change in the log odds of the dependent variable for a one-unit change in the independent variable.

Can handle both categorical and continuous variables: Logistic regression can handle both categorical and continuous independent variables, making it a versatile method for modeling binary outcomes.

## Limitations:

Assumes linearity: Logistic regression assumes a linear relationship between the independent variables and the log odds of the dependent variable. If this assumption is violated, the results may be inaccurate.

Sensitive to outliers: Logistic regression can be sensitive to outliers, which can have a significant impact on the results.

## Suggestion:

When we are dealing with huge datasets & above disavantages starts effecting the model, then using CatBoost Classifier can provide better results.
