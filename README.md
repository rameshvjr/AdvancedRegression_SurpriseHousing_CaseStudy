# Case Study on Advanced Regression: Surprise Housing Company

Objective is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement:
    - A US-based housing company named Surprise Housing has decided to enter the Australian market. 
    - The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
    - For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file 

- Objective
    - Objective is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
    - The company wants to know:
        - Which variables are significant in predicting the price of a house, and
        - How well those variables describe the price of a house.
        - Determine the optimal value of lambda for ridge and lasso regression.

- Business Goal
    - Model the price of houses with the available independent variables. 
    - This model will then be used by the management to understand how exactly the prices vary with the variables. 
    - They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
    - Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- Data set used: train.csv along with Data Dictionary provided in case study.


## Conclusions
-Final Observations / Compilation of Inferences from Part 1 of this activity:

The variables significant in predicting the price of a house are:
    - GrLivArea
    - Neighborhood_Crawfor
    - Exterior1st_BrkFace
    - OverallQual
    - Functional_Typ
    - YearBuilt
    - TotalBsmtSF
    - Condition1_Norm
    - Neighborhood_Somerst
    - OverallCond
    - SaleCondition_Alloca
    - Neighborhood_StoneBr
    - OverallQual

How well those variables describe the price of a house? 
    - Here will see only top few variables
        - GrLivArea:an increase of 1 square foot of house area above ground, the price will increase by 1.09 to 1.11 times
        - OverallQual: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.06 to 1.07 times
        - Functional_Typ: if the home functionality is typical, then the price of house will increase by 1.07 times
        - Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by 1.06 to 1.07 times.

In a similar manner, we can deduce how well each variable describes the price of a house.

Finally, 
    - Optimal value of lambda for Ridge Regression = 10 (alpha)
    - Optimal value of lambda for Lasso = 0.001 (alpha)

Part 2 - Subjective questions have been answered and submitted in PDF (AdvancedRegression_Assignment_SubjectiveQuestions_Part2.pdf)


## Technologies Used
- Python 3.0
- Jupyter Notebook
- Libraries used in this case study:
    - numpy: version 1.21.5
    - pandas: version 1.4.2
    - matplotlib: version 3.5.1
    - seaborn: version 0.11.2
    - sklearn
    - statsmodels


## Acknowledgements
- This project was inspired by efforts of some of our UpGrad Alumini students, Coach Mr. AKASHDEEP MAKKAR, PRAVEERSINH PARMAR's page in Kaggle
- References: 
    - https://stackoverflow.com/
    - https://pynative.com/
    - Few other online knowledge hubs / information available on internet.
    

## Contact
Created by [@rameshvjr] - feel free to contact me!