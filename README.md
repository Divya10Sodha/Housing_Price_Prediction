# Housing Price Prediction Using Advanced Regression


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
**Problem Statement**
- To build a regression model for Surprise Housing, a US-based housing company which wants to enter the the Australian market. The company intends to use data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For this, they have collected data from the sale of houses in Australia.

**Business Goal**
- To model the price of houses with the available independent variables, which will be used by management to understand how the prices vary with the variables and accordingly they can manipulate the strategy of the firm and concentrate on areas that will yield high returns.
    
**Analytical Goals**
    1. Which variables are significant in predicting the price of a house, and
    2. How well those variables describe the price of a house.
    3. Use Regularization and also determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Data is cleaned and prepared, features are selected through RFE by coarse tuning and model is regularized using ridge and lasso regression techniques.
- The Optimal value of lambda for ridge is 0.0001 and for lasso is 50.
- Lasso regression seemed to perform better than ridge with a train R-square of 0.923 & test R-square value of 0.903
- The top 10 variables significant in predicting the price of a house based on Lasso Regression are - 
    1. GrLivArea    
    2. BsmtFinSF1                
    3. OverallQual               
    4. NoYearBuilt               
    5. BsmtUnfSF                 
    6. OverallCond               
    7. Neighborhood_StoneBr      
    8. GarageArea                
    9. Neighborhood_NoRidge      
    10. KitchenQual_TA          

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.0.5
- Numpy - version 1.19.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.0
- Sklearn - version 0.23.1
- Statsmodels - version 0.11.1
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the Upgrad Team and IIIT Bangalore and helped me to learn a lot about the Exploratory Data Analysis.
- I would be greatful to the IIIT Bangalore as well as the Upgrad Team for providing opportunity to work on such real-time project.



## Contact
Created by [@Divya10Sodha] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->