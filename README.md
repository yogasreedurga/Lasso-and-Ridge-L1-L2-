# SUPRISE HOUSING - PREDICTING THE PRICE OF HOUSES
The main objective of this programming assignment is to build a regularized linear regression model for the prediction of Sales Price of houses for a US based housing company named Surprise Housing

## Table of Contents
* [General Info](#general-information)
* [Techniques Used](#Techniques-used)
* [Tools/libraries used](#Tools/libraries used)
* [Conclusions](#conclusions)


## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

-  Which variables are significant in predicting the price of a house, and
-  How well those variables describe the price of a house.
-  Also, determine the optimal value of lambda for ridge and lasso regression.

## Techniques Used
-  Reading and understanding the data
-  Data cleaning - converting datatypes, dropping redundant columns,creating dummy variables,etc.,
-  Data Visualization - Visualizing numerical and categorical data
-  Preparing the data for modelling - Train-test split,Rescaling the variables
-  Building a model using Multiple Linear Regression
-  Tuning with Regularization parameter
-  Model Evaluation

## Tools/libraries used
-  numpy
-  sklearn
-  statsmodels
-  seaborn
-  pandas

## Conclusions
The variables which help in predicting the housing prices are:

*LotArea - Lot size in square feet
*Neighborhood_Edwards - Physical locations within Ames city limits - Edwards
*Exterior1st_CBlock - Exterior covering on house with Cinder Block
*GarageType_Attchd - Garage attached to the home
*MSZoning_RH - High density of population in a residential zone
*OverallCond - Overall Condition of the house
*Condition1_PosA - Proximity to various conditions - Adjacent to postive off-site feature
*ExterQual - The quality of material on the exterior
*MSZoning_RM - Medium density of population in a residential zone
*SaleType_Oth - Type of sale

The optimal value of lambda for Ridge and Lasso are:

-  Lasso : 0.001
-  Ridge : 20

## Contact
Created by [@yogasreedurga] - feel free to contact me!
