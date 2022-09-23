# House-Price-Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
Using the data set of sales of houses in Australia, Company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
Using the data set of sales of houses in Australia, Company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Business Goal:
Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
Determine the optimal value of lambda/alpha for ridge and lasso regression.
This model will then be used by the management to understand how exactly the prices vary with the variables.
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
Achieve the R2 score on both Ridge and Lasso Models. The follwing factors influence the house price the most as demosntrated by both the models:-
Overquality of the house
Total rooms above grade (does not include bathrooms)
Lot size in square feet
OverallCondition of the house
Basement full bathrooms in the house
Full bathrooms above grade in that house
GarageCars: Size of garage in car capacity in that house
Condition2: Proximity to various conditions (if more than one is present)
Street: Type of road access to property
GarageArea: Size of garage in square feet


## Technologies Used
Python and their libraries are using:
Import all the libraries in to the jupyter notebook i.e..,
import numpy as np
import pandas as pd
from pandas import DataFrame
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings("ignore")
import os
from scipy.stats import norm
from scipy import stats
%matplotlib inline
from sklearn.preprocessing import MinMaxScaler
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import PowerTransformer
from sklearn.feature_selection import RFE
from sklearn import linear_model
from sklearn.linear_model import LinearRegression
from sklearn.linear_model import Ridge
from sklearn.linear_model import Lasso
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import r2_score
from sklearn.metrics import mean_squared_error
from statsmodels.stats.outliers_influence import variance_inflation_factor

## Acknowledgements
Give credit here.
- This project was inspired by... UpGrad Learning Platform
This project was based on @ https://learn.upgrad.com/course/3064


## Contact
Created by @ https://github.com/Ravitejanaga/House-Price-Prediction.git) - feel free to contact me!

