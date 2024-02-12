# Bike Sharing Demand Prediction Model- Linear Regression
> To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

### Problem Statement
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

### Business Requirment:
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

### Given Data 

- Bike sharing csv file with Bike Sharing records of the yr 2018 and 2019   
- Dictionary file to understand the variables


## Technologies Used

Python Libraries:

- pandas
- numpy
- seaborn
- matplotlib.pyplot
- sklearn
- statsmodel


## Conclusions

- All the positive coefficients like temp,yr indicate that an increase in these values will lead to an increase in the value of cnt.
- All the negative coefficients lihe hum and windndspeed indicate that an increase in these values will lead to an decrease in the value of cnt.
- Temp is the most significant with the largest coefficient.
- Bike rentals is more for the month of september
- The rentals reduce during holidays



## Acknowledgements

- Reference Material - Upgrade Assignment and Live Session on Linear Regression


## Contact
Created by [@https://github.com/AntonyJohnSundar] - feel free to contact me!


