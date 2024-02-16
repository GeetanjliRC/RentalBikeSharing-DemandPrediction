# Bike Shaing Demand Prediction_Supervised Ml Regression Project
Currently, Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Business Objective
The project aims to address the challenge of making rental bikes available and accessible to the public at the right time by predicting the demand for rental bikes at different times of the day. The ultimate goal is to help cities optimize their bike-sharing systems by predicting demand and allocating resources accordingly.
We need to develop a machine learning model that can accurately predict the number of rental bikes required at each hour in urban cities. This is crucial for ensuring a stable supply of rental bikes and minimizing waiting times for users.

## Project Summary
We have a dataset of 8760 rows and 14 columns. After performing Data preprocessing and feature engineering, we applied squareroot transformation to get a normal distribution and scaled our data using MinMax scaler. Finally we split our data into train and test in 80-20 ratio, making it ready to fit into a machine learning model, we implemented the various models and calculated the various stastical parameters for the performance. We performed hyperparameter tuning for best results and Considering adjusted r^2 score on test stastics we have selected Random Forest as best performing model with accuracy of 91.37%.

## Observations on EDA
It is observed that 95% of days are working (not holiday) and 4.9% of days are holidays in the data given.

The captured data falls under the range start date = 2017-01-12 and last date = 2018-12-11

The sum of Bikes rented on No Holiday is 5956419 and on Holiday is 215895

The sum of bikes rented on Functioning Day is 6172314 and on a non-functioning day is 0

The total bikes rented in 2018 is 5986984 and in 2017 is 185330

It is observed that on a functioning day the bike rented sum is zero, means that on a non functioning day there were no bikes that were rented.

Bikes demand is more during Summer and less during the winters

It is observed that the bikes are rented maximum at 8 hours(8am) and 18 hours(6pm) usually, the demand of bikes is mostly depended on the hour of the day, This can be an indication that people are renting bikes to travel to office and coming back from office.

People prefer to drive bike when the wind speed is moderate between 0.3 to 3.4. there is a minor impact of wind speed on the bike renting preference

there is positive growth from second week and it is observed that on 25th week of the 2nd year saw max bikes rented

When visibility is 2000 people prefer the most to rent bikes Demand of rental bikes is on the low soalar radiation i.e 0.0

People do not prefer to rent a bike when there is a solar radiation > 0.05


