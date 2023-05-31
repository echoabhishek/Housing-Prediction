# Housing Price Prediction - Lasso & Ridge Regularization

## Assignment Overview
Surprise Housing, a US-based company, aims to enter the Australian housing market. To make profitable investments, they utilize data analytics to acquire properties below their market value and sell them at a higher price. They have collected a dataset of house sales in Australia and now require a regression model with regularization to predict the actual value of potential properties. This will help them decide whether to invest in those properties or not.

The company's objectives are:
1. Identify the significant variables that contribute to predicting house prices.
2. Assess how well these variables explain the variation in house prices.
3. Determine the optimal lambda value for both Ridge and Lasso regression techniques.

By developing a regression model with regularization, Surprise Housing can gain insights into the important predictors of house prices and evaluate their impact. The optimal lambda value will enable them to strike the right balance between model complexity and generalization performance.


## Table of Contents
* Data Understanding/Cleaning, Univariant/Bivariant analysis/Data Visualisation/Building a linear module with all the variables/Residual Analysis of the train data/Model Evaluation/Calculating R-squared score on test data/Lasso and Ridge regularisation
* Numpy,Pandas, Matplotlib, Seaborn and Sklearn libraries used
* conclusions
* Course Lectures

<!-- You can include any other section that is pertinent to your problem -->

## General Information
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
- The R2 score for the test dataset is 0.797 for Linear, 0.798 for Ridge and 0.8006 for Lasso Regression.

- Lasso Regression model can be used to make inferences. This is based on high Test R2 score and RMSE values using best alpha.

- From R2 and adj R2 value of both train and test dataset we could conclude that the selected variables can explain more than 80% of House price prediction. 

- The top 10 variables based on the coeffiencients selected inorder and significant in predicting the house prices are.
    
    __From Linear and Ridge Regression:__
    OverallQual_10, LotArea, OverallQual_9, OverallQual_8, MasVnrArea, KitchenAbvGr, 3SsnPorch, OverallQual_7, OverallCond_9, 
    LowQualFinSF
     
    __From Lasso Regression:__
    OverallQual_10, OverallQual_9, LotArea, OverallQual_8, MasVnrArea, KitchenAbvGr, OverallQual_7, OverallCond_9, WoodDeckSF, 
    HalfBath   
    

- The optimal value of lambda for Ridge is 0.2 and for Lasso regression is 0.0001.
    
- Using Linear regression, we can predict the house price with 0.79% confidence.
- Using Ridge regression, we can predict the house price with 0.79% confidence.
- Using Lasso regression, we can predict the house price with 0.80% confidence.

## Technologies Used
* Python - version 3
* NumPy - version 1.21.5
* Pandas - version 1.4.4
* Seaborn - version 0.11.2
* Matplotlib - version 3.5.2
* Sklearn - version 3.8


## Author
Created by [mail2abhishekarora@gmail.com] - feel free to reach me out @+91-7503995004.
