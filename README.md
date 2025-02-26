# Project Name
> Outline a brief description of your project. BoomBikes, a US-based bike-sharing provider, has recently experienced a significant decline in revenue due to the ongoing COVID-19 pandemic. Struggling to sustain itself in the current market conditions, the company has decided to develop a strategic business plan to boost revenue once the lockdown ends and the economy stabilizes.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. The company wants to know:

Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
* Build a linear regression model to find the variables which have a significant impact on the demand for shared bikes.
* What is the background of your project?
* What is the business probem that your project is trying to solve?: variables that affect the demand for shared bikes and the extent of their impacy
* What is the dataset that is being used?


## Conclusions
1. The temperature or weather conditions form a weightage nearly 66% (temp+Summer+Winter+clear_partlycloudy)as the cause of more demand, here it is not clear as to why the weather condition "Spring" has a negative correlation with the target variable

2. The variable "yr" has a weightage of nearly 24% for increase in bike demand
3. Key variables influencing the model:
   Temp: Higher temperatures generally increase bike demand.

   Humidity: Higher humidity negatively impacts bike rentals.

   Windspeed: Extreme windspeed conditions reduce bike usage.

   Season & Weather Conditions: Demand fluctuates based on seasonal variations and weather conditions.



## Technologies Used
- Python - version 3.11.4
- Matplotlib - version 3.7.1
- Numpy - version 1.24.3
- Pandas - version 1.5.3
- Seaborn - version 0.12.2
- Statsmodels - version 0.14.1
- Scikit-learn - version 1.4.2


## Acknowledgements
- This project was inspired by Upgrad


## Contact
Created by [@darekarankita0] - feel free to contact me!
