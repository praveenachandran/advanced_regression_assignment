# Project Name
> Advanced Regression - House Price Prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

 

Also, determine the optimal value of lambda for ridge and lasso regression.

 

Business Goal 

 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

 

## Conclusions
The optimal regularization parameter, λ, obtained for Ridge and Lasso regression is as follows:

Ridge: 2.0
Lasso: 0.0001
The corresponding R-squared values for both Ridge and Lasso models are:

Ridge: Train = 0.930, Test = 0.896
Lasso: Train = 0.927, Test = 0.903
Regarding Mean Squared Error, the values for Ridge and Lasso are:

Ridge: 0.00297
Lasso: 0.00280
Notably, Lasso exhibits a slightly lower Mean Squared Error compared to Ridge.

Moreover, due to Lasso's feature reduction capability (by shrinking coefficients towards zero) and its enhancement of model interpretability through coefficient magnitude consideration, Lasso outperforms Ridge in this aspect.

Consequently, based on Lasso Regularization, the top five predictive variables are identified as follows:

--- OverallQual: The quality of overall material and finish positively correlates with house price.

--- GrLivArea: Larger living area square footage tends to increase house price.

--- YearBuilt: House age positively influences price.

--- Total_sqr_footage: Overall square footage of the house positively impacts price.

--- Neighborhood_StoneBr: The location in Stone Brook has a positive association with house price.


## Technologies Used
pandas 
numpy 
matplotlib 
seaborn 
sklearn 
statsmodel 


## Acknowledgements

- This project was case study



## Contact
Created by [@praveenachandran] - feel free to contact me!
