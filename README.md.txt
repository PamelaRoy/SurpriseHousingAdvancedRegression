# Project Name
> Surprise Housing – Advanced Linear Regression assignment

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The company is looking at prospective properties to buy to enter the market. 
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house


## Table of Contents
* General Information
* Technology used
* Model building and training 
* Prediction and evaluation on test data


## General Information

Using the data provided design a model to identify : 
	-Which variables are significant in predicting the sale price of the houses.
	-How well those variables describe the sale price


## Technology used
- Python is used to design the Linear regression model . 
- Google Colab is used to do the coding
- Google Drive is used  to store the data file
- Important libraries used are 
 	- pandas
	- numpy 
	- sklearn 
	- statsmodel 

## Conclusions

Perform regularization using Ridge & Lasso .
Predictor values reduced to 35 from 258 .  
Best performance shown in both train & test set of data by - Ridge Regression 
   - Hyperparameter used - 0.05 
   - Top ten variables chosen by Ridge regression are : 
	'LotArea' 'YearBuilt' 'BsmtFinSF1' 'TotalBsmtSF' '1stFlrSF'
        '2ndFlrSF' 'GrLivArea' 'BedroomAbvGr' 'KitchenAbvGr' 'GarageArea'
In Lasso Regression Hyperparameter used is - 0.0001


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad EPGP ML&AI course
- References if any - Study materials from Upgrad


## Contact
Created by Pamela Roy 
email : bhattacharya.pam@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->