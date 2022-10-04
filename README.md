# Bike rental demand analysis

## Problem Statement
A Bike-rental provider has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

The company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.  Specifically, they want to understand the factors affecting the demand for these shared bikes. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

## Business Goal
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Approach
Created a linear regression based model that describes the effect of various features on price. Finally highighted the key features that management need to focus on for business stratergy.

### Step Involved
    1. Reading and understanding data
    
    2. Data Cleaning
    - Removing skweed columns
    - Mapping Categorical Columns
    
    3. Data Visualization
    - Performing EDA and Understanding Variables
    - Checking Co-relation between variables
    
    4. Data Preparation
    - Creating Dummy Variables
    - Dividing Data into test-train
    - Performing Scaling(Min-Max)
    
    5. Data Modelling and Residual Analysis
    - Creating linear regression model using mixed approach (i.e. using RFE & VIF/p-value for feature selection)
    - Check various assumptions
    - Report Final Model
    - Residual Analysis
    
    6. Prediction and Evaluation
    - Evaluate the model on the basis of test data
