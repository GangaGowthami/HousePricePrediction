#  House Price Prediction - Assignment Solution 

## Introduction
In this assignment we need to build a model for the prediction of price of a House.



## Problem Statement:

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

Essentially, the company wants to know —

Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

# Business Goal
Business Goal We are required to model the price of houses with the available independent variables. It will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high rewards. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


# steps Performed

- Step 1: Reading and Understanding the Data
- Step 2: Missing Value Treatment
- Step 3: Data Visualisation
- Step 4: Data Preparation
      - Splitting the data into Train and Test Sets
      - Feature Scaling
- Step 5: Building Model
       - Dividing into X and Y sets for the model building
       - Apply Lasso Regression
       - Apply Ridge Regression
- Step 6: Model Evaluation
       - Check Lasso Model Evaluation
       - Check Ridge Model Evaluation




## Technologies Used
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- sklearn

## Insights:

- With Lasso model,R2 score on training set is 93.8% and R2 score on testing set is 90.8% which is good. which is good. Model has performed well on train and test data.
- With Ridge model, R2 score on training set is 93.8% and R2 score on testing set is 90.6% which is good. which is good. Model has performed well on train and test data.
- Model evaluation results for both lasso and ridge model on train data as well as test data are at par. Ridge model is performing slightly better.
- We have evaluated models based on 270 features. Since most of the features are eliminated by Lasso hence we will select Lasso as the best model.

# Conclusion
- Final model slected is Lasso Regression with alpha 0.0001

# Contact
Created by [@GangaGowthami] - feel free to contact me!

