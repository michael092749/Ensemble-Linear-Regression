# Advanced Regression Techniques

This notebook is a submission to a kaggle competition whereby the prices of houses are to be predicted using advanced linear regression models. https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

## Problem Statement:

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

Test and training data sets provided.

## Goals:

- To identify the variables affecting house prices, e.g. area, number of rooms, bathrooms, etc.

- To create a linear model that quantitatively relates house prices with variables such as number of rooms, area, number of bathrooms, etc.

- To know the accuracy of the model, i.e. how well these variables can predict house prices.

## Result

This notebook conducts feature engineeering and compares different regression models. It was found that an ensemble model regressor consisting of a Gradient Boost regressor and a Kernel Ridge Regressor performed best.

Results were tested on the test data set, and this code performed in the **Top 6%**
