# TelecomChurn
> In the telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. It is very important for any telecom operator to prevent the present customers from churning to other operators. As a data scientist, in this case study we are building various ML models which can predict if the customer will churn or not in a particular month based on the past data. We finally choose the best model and use it to predict for the data in test.csv

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Models Built](#models-built)
* [Contact](#contact)

## General Information
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate.

Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

Our goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.

The steps that we have followed below are as follows:

Data Understanding, Preparation, Pre-processing
Feature Engineering and Variable Transformation
Exploratory Data Analysis
Model Building
Model Recommendations
Kaggle Submission

## Conclusions
- Random Forest and SVM both perform well on the given dataset. Models with PCA and without PCA have been executed.
- Random Forest models are not just accurate but also perform better than SVM on other metrics like sensitivity and specificty. Therefore, we will choose rfc4_model for predictions on the test data. It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
- The model rfc1_model is being used to identify the top predictors of customer churn. It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks. The top predictors are displayed below in the next section.
- log1_pca_model - This is a logistic regression model. Although this model has lower accuracy compared to other models, the sensitivity of this model is more than 80% which is the highest among all models. We would recommend this model as it identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn. This is given by the metric sensitivity. Logistic regression models are simple and consume lesser computational resource.


## Models Built
- Model #1 - Logistic Regression
- SVM
- Random Forest with PCA
- XGBoost
- Random Forest without PCA

## Contact
Created by [@jenifer2409] - feel free to contact me!

 
