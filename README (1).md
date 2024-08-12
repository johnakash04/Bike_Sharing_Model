# Bike_Sharing_Model
Bike sharing Case Study


Problem Statement:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


The company wants to know:


Which variables are significant in predicting the demand for shared bikes.

How well those variables describe the bike demands


Goals :

Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables.

It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.

Further, the model will be a good way for management to understand the demand dynamics of a new market.


Step 1: Reading and Understanding the Data

Step 2: Encoding the Labels & Visualization

 Bike Rentals are more during the Fall(Monsoon) season.
 
 Bikes seem to be rented more in Partly cloudy weather
 
 Bikes seem to be rented more on working days.Bike Rental popularity has increased in 2019 when compared to 2018.
 
 Bike Rentals are maximum on Sunday and Monday
 
 Bike Rentals are observed at higher temperatures.
 
 Bike Rentals are observed at higher "feel-like" temperatures.
 
 Temperature being directly proportional to Humidity, Bike Rentals are making during high humidity.
 
 Wind speeds increase with a greater temperature difference.Wind speed near the surface is most highly correlated with the temperature.
 
Step 3: Visualizing the Relationship among variables 

 It is observed that atemp and temp are highly correlated and one can be dropped to avoid multicollinearity
 
Step 4 : Dealing With Categorical Variables

Step 5: Splitting the Data into Training and Testing Sets

Step 6: Building a linear model

Step 7: Residual Analysis of the train data

Step 8: Making Predictions

Conclusion:
The top 5 variables that are seen effecting and benefitting the Bike Rental count are as follows:
Spring season : -0.6842

Temperature : 0.3999

Mist : -0.3647

Sun : 0.2749

working_day : 0.2327

Assumptions of Linear Regression:

The error terms are normally distributed.

The training and testing accuracy are nearly equal hence there is no Overfit/Underfit situation.

The predicted values have linear relationship with the actual values.

Thankyou
 
