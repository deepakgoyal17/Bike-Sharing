# Bike-Sharing
Create a model where you have to build a multiple linear regression model for the prediction of demand for shared bikes. 

# Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

# Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

# Conclusions:

The equation of best fitted surface based on model lm:
cnt=0.293426 + (0.360252 x temp) + (-0.114046 x windspeed) + (-0.096127 x season_spring) + (0.079929 x season_winter) + (-0.100545 x mnth_dec) + (-0.074138 x mnth_feb) + (-0.100478 x mnth_jan) + (-0.066659 x mnth_jul) + (-0.104161 x mnth_nov)  + ( 0.256542 x yr_1) + ( 0.028241  x weekday_Sat) + ( -0.075520  x weathersit_Cloudy) + ( -0.264098  x weathersit_Snow)

Below are the gignificant variables to predict the demand for shared bikes
 'temp', 'windspeed', 'season_spring--season', 'season_winter--season','mnth_dec---month', 'mnth_jul --month', 'mnth_nov --month', 'yr_1---year(2019)', 'weekday_Sat --weekday','weathersit_Snow--weathersit','weathersit_CLoudy--weathersit'

Technologies Used
sklearn pandas statsmodels matplotlib numpy 

Contact
er.deepakgoyal@gmail for more information on the same
