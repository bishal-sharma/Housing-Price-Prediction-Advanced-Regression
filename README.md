# Housing Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.
- Understanding of the important variable provide the business with the oppertuinity to align with the trend
- A sales data with 80 diferent variable along with sales price is provided for analysis and model building

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Linear Regression. Ridge and Lasso Regression is used to identify the best model
- R2 scores from diferent methods
    - Linear regression with RFE : Tran R2 0.908039, Test R2 0.777925
    - Ridge regression with RFE : Tran R2 0.938428, Test R2 0.789859
    - Lasso regression with RFE : Tran R2 0.826326, Test R2 0.808314
- Lasso regression is able to describe the data wth just 36 variables with very good accurecy
- The top 5 Predictors are :
    - GrLivArea: Above grade (ground) living area square feet
    - OverallQual: Rates the overall material and finish of the house
    - Neighborhood (Northridge) : Physical locations within Ames city limits
    - GarageCars: Size of garage in car capacity
    - BsmtExposure: Refers to walkout or garden level walls

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was based on Upgrad Advanced Regression


## Contact
Created by [@bishal-sharma] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->