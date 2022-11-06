# Project Name: Advanced Regression, Surprise Housing Prediction Analysis
> Problem Statement:

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and how well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## General Information
- Make a model to predict the Sale Price of houses based on given factors/variables
- Build Lasso and Ridge Regression Models and determine which to choose based on their performance
- Thep project is an assignment for an ML/AI course at IIIT-B and UpGrad


## Conclusions
- The top five variables affecting the SalePrice are 
	1. GrLivArea: Above grade (ground) living area square feet 
	2. OverallQual: Rates the overall material and finish of the house
	3. TotalBsmtSF: Total square feet of basement area
	4. OverallCond: Rates the overall condition of the house
	5. YearBuilt: Original construction date
- For ridge regression, the optimum alpha was 100 with an R2 train score of 0.95 and test score of 0.90
- For lasso regrsesion, the optimum alpha was 0.01 with an R2 train score of 0.94 and test score of 0.91



## Technologies Used
- numpy - version 1.23.3
- pandas - version 1.4.4
- matplotlib - version 3.5.3
- plotly - version 5.10.0
- seaborn - version 0.12.0
- statsmodels - version 0.13.2
- sklearn - version 0.24.2
- scipy - version 1.9.1

## Acknowledgements

- The project is done solely by Abbas Bagwala as part of an assignment for IIIT-B and UpGrad's course on ML and AI

## Contact
Created by Abbas Bagwala[@sanfracato] - feel free to contact me!
