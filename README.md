# Project Name
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* Problem Statement
* Conclusions
* Technologies Used
* Acknowledgements

### Business Objectives
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## General Information
- Provide general information about your project here.
### Exploratory Data Analysis
   Data Understanding
   Data Cleaning
   Univariate Analysis
   Bivariate Analysis
   Dummay variable creation for converting catogorical variables into numerical variables
   Splitting data into Train and test sets
   Building Linear Model using RFE 
- What is the background of your project?
	
- What is the business probem that your project is trying to solve?
	BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19
- What is the dataset that is being used?
	Day Data Set

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- cnt seems to have correlation with year and temp variable
- Misty and Humidity show correlation
- Spring season with Jan and Feb momth and Summer season with May Month and Winter season with Oct month show good correlation
- VIF doesnt seems to be affected much after dropping few of the variables. Lets proceed with STATS model to observe better model.
- We can cosider the above model , as it seems to have very low multicolinearity between the predictors and the p-values for all the predictors seems to be significant.
- F-Statistics value of 252.3 (which is greater than 1) and the p-value of 2.69e-170 i.e almost equals to zero, states that the overall model is significant


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - 1.3.4
- numpy - 1.20.3
- matplotlib - 3.4.3
- seaborn - 0.11.2
-SKlearn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- Day Dataset
- Data Dictonary



## Contact
Created by [@Neelima123] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->