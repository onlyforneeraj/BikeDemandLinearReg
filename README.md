# Project Name : Bike Demand Prediction Project


> Description : A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Goal of the project is to predict the bike demand to effectively manage the company operations.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- What is the background of your project?
In an attempt to have a mindful business plan, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

- What is the business problem that your project is trying to solve?
Specifically, company wants to understand the factors affecting the demand for these shared bikes in the American market. They want to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands.


- What is the dataset that is being used?
day.csv

## Conclusions
Model is able to explain the change in demand well. R2 value on the test data comes out to be 0.723. R2 value of the model on the training data is 0.792.
Adjusted R2 value on the test data comes out to be 0.657. Adjusted R2 value of the model on the training data is 0.789. Linear regression equation of the model is:

cnt = 626.3026 + 1999.4631 * yr -783.3733 * holiday + 5602.8603 * atemp - 1101.0737 * windspeed - 2147.8988 * light_rain + 567.5711 * summer + 1074.8253 * winter

Conclusion from the attributes:
atemp - Temperature of the day affects the demand of the bikes significantly. 
Season -  In summer and fall season, demand seems to be better than other seasons. 
Yr - Fact that demand is higher in 2019 than 2018 shows that demand is growing year on year.
Mnth - May to October months have higher demand than other months in year. 
Holiday - Demand is lower on holidays than other non-working days.
Weekday - There is no remarkable variation in demand over the weekdays.
Workingday - Working days have higher demand for bikes than the non-working days.
Weathersit - Clear and partly cloudy days have better demand for bikes than the days when light or heavy rain occurs.

## Technologies Used
- Python - version 3.6
- pandas - version 1.1.5
- numpy - version 1.20.3
- matplotlib - version 3.3.4
- seaborn - version 0.11.2
- sklearn - version 0.24.2
- statsmodels - version 0.12.2



## Acknowledgements
- This project is an assigment by Upgrad and IIIT-B as a part of Exploratory Data Analysis


## Contact
Created by [@onlyforneeraj] - feel free to contact me!


License: This project is open source and available under the general use License.
