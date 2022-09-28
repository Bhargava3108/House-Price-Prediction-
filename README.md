# House Price Prediction based on Ridge and Lasso

>  The Project is the identify the property in Australian market for the US based company . The Aim of the project is to predicting the price of a house using Ridge and Lasso

Outline a brief description of your project.

   A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia
    
The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house. 

The optimal value of lambda for ridge and lasso regression.

 
Business Goal 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info]  We have analyzed the property in Australian market for the US based company and then we apply different methods to clean the data and to build a model on Ridge and Lasso regression.
* [Technologies Used]  Python,GIT,GITHUB,PDF
* [Conclusions] Below are the details
* [Acknowledgements] 



## General Information

- Provide general information about your project here.

- What is the background of your project?
                The Back ground of the project is to analyze property in Australian market for the US based company. The data contain 1460 records along with 81 columns. The Ridge & Lasso regression model is being used as the methodology to analyze the data.
                
- What is the business problem that your project is trying to solve?
               The model the price of houses with the available independent variables. 
               This model will then be used by the management to understand how exactly the prices vary with the variables.
               They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
               The model will be a good way for management to understand the pricing dynamics of a new market.

- What is the dataset that is being used?
            The Train data is the master details dataset and Data dictionary is to understand the column meaning.



## Conclusions

By Comparing the mean squared error of Ridge and Lasso where Ridge value is 0.013646655194396364 and 
Lasso Value is 0.013622928660692247. we can see that Lasso values are slightly lower than the Ridge value.

Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), 
Lasso has a better edge over Ridge.


Hence based on Lasso, the factors that generally affect the price are the Zoning classification, 
Living area square feet, Overall quality and condition of the finished house, Foundation type of the house, 
Number of cars that can be accomodated in the garage, Total basement area in square feet
and the Basement finished square feet area

Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price       of a house with the equation below.

The Equation :

    Log(Y) = C +  0.121 * (MSZoning_RL) + 0.108 * (GrLivArea) + 0.077 * (MSZoning_FV)+ 0.072 * (OverallQual)+ 
    0.049 * (TotalBsmtSF) + 0.045 * (OverallCond) + 0.042 * (Foundation_PConc) + 
    0.037 * (GarageCars) + 0.033 * (BsmtFinSF1) -0.02 * (builtorremodelledage) ++ Error term(RSS + alpha * (sum of absolute value of coefficients)

When the market value of the property is lower than the Predicted Sale Price, its the time to buy.


## Technologies Used

-python - version 3.6.9 pandas - version 1.0.3 matplotlib - version 3.2.1 seaborn - version 0.11.1


## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@Bhargava3108] - feel free to contact me!
