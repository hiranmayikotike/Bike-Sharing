Business Case:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

Data Understanding and Model building using below steps:

Step-1 : Understanding the data:
 - Importing the libraries and reading the data
 - Check the dataset for anomolies
 - Fix data types, missing values or impute
 - Visualize the data

Step-2: Data Preparation:
 - Create dummy variables and binary numbers
 - Split the data into trainning and set
 - Re-scale the variables

Step-3: Trainning the Data:
 - Use RFE to check the top 10 variables
 - Use manual and business understanding to check other variables also.
 - Residual Analysis:

Step-4: Plot residual errors
 - Prediction on Test setup:

Step-5: Use same variables to test the test set
 - Using R2 compare the r-score

Final Variables :
Finally, we get important variables which are Temprature, Windspeed, Year 2019, Summer Season, Winter Season, Cloudy weather, Light rain Weather and Jannuary, September and November and December Months, wednesday and Tuesday.

Equation for the model is:
y = 0.1209 + temp - 0.1552 x windspeed + 0.2332 x Year_2019 + 0.894 x summer + 1.48 x cloudy + 0.1281 x winter + 0.0978 x sept - 0.2785 x light_rain