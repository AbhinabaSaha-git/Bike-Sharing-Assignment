# Bike Sharing assignment
>The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. It allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
- day.csv is the dataset used

## Conclusions
### Created a linear model that describes the effect of various features on demand.

##### below variables are significant in predicting the demand for shared bikes

- yr
- holiday
- workingday
- temp
- x0_2 (summer)
- x0_4 (Winter)
- x1_9 (September)
- x3_3 (weathersit:Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)

-R2 Score compare:
-R2 Score for Train data set is : 0.794
-R2 Score for Test data set is : 0.777


## Technologies Used
- used language python.
- Modules: numpy, pandas, matplotlib, seaborn
- for ML - sklearn and statsmodels. 

## Acknowledgements
- References :  [towardsdatascience](https://towardsdatascience.com/) and [geeksforgeeks](https://www.geeksforgeeks.org/)


## Contact
Created by [Abhinaba Saha](https://github.com/AbhinabaSaha-git) 


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
