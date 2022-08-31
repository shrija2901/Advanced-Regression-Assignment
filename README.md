# Project Name
Advanced Regression Assignment for Predicting housing prices


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Predicting house prices using advanced regression techniques such as Ridge and Lasso.

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the 'test.csv' file uploaded in the repository.

The company is looking at prospective properties to buy to enter the market. This repository builds a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
-Which variables are significant in predicting the price of a house?
-How well those variables describe the price of a house?

Using GridSearchCV the model arrives at a final optimum lambda to determine the house prices using ridge and lasso regression.

## Conclusions
Since Lasso helps in feature reduction (as the coefficient value of some of the features 
become zero), Lasso has a better edge over Ridge and should be used as the final model


## Technologies Used
- numpy
- pandas
- sklearn 
- statsmodels

## Acknowledgements

This project is done by Shrija Kale


## Contact
Created by [@shrija2901] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->