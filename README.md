# Bike Sharing Demand
> The objective of this case study is to understand the factors affecting the demand for shared bikes in the American market. The company wants to know the variables that are significant in predicting the demand for shared bikes. They also want to know how well those variables describe the bike demands. 

## Table of Contents
* [Problem Statement](#Problem-statement)
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## Problem Statement
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Business Goal
- The business goal is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market

## Conclusions
- The top 3 factors affecting the count of rental bikes are:  
1. Temperature - The coefficient of temp is 0.5636, which means that a unit increase in temp will increase the count of rental bikes by 0.5636 units.
2. weathersit_3 - The weathersit_3 indicates ` Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds`. The coefficient of weathersit_3 is -0.3070, which means that a unit increase in weathersit_3 will decrease the count of rental bikes by 0.3070 units.
3. yr  - The coefficient of yr is 0.2308, which means that a unit increase in yr will increase the count of rental bikes by 0.2308 units. Thus we can interpret that the count of rental bikes increases year on year by 0.2308 units.


## Technologies Used
- Python - version 3.10.10
- Numpy - version 1.24.2
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Seaborn - version 0.12.2
- sklearn - version 1.2.2
- statsmodels - version 0.13.5
- plotly - version 5.14.1


## Acknowledgements
- This project is part of the course Executive PG Programme in Machine Learning and Artificial Intelligence offered by UpGrad.
- The dataset is provided by UpGrad.


## Contact
Created by [@robinsonrajan] - feel free to contact me!
