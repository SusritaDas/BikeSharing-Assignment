### BoomBike Sharing Assignement 

#### Overview :
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted myself to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

#### Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

#### Dataset used :
CSV file and data dictionary is provided. In the dataset provided, you will notice that there are three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number casual users who have made a rental. The variable 'registered' on the other hand shows the total number of registered users who have made a booking on a given day. Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. The model should be built taking this 'cnt' as the target variable.

#### Process done :
1. Importing important libraries
2. Load and read the dataset
3. Data analysis
4. Data cleaning and correction
5. Univariate analysis of cnt with other columns
6. Bivariate analysis
7. Multivariate analysis
8. Model preparation
9. linear regression
10. creating OLS modules (2)
11. making predictions
12. calculating r2 on the best model
13. Predictions and suggestions to the company or observations 

### Observation/Prediction/Inference
Key Focus Areas for the Company:
Temperature Sensitivity:
The data suggests that bike usage is temperature-sensitive. People are less likely to use the service at extremely high or low temperatures. To optimize operational costs and enhance profitability, the company should consider operating at reduced capacity during extreme temperature conditions. Focusing on registered customers during such periods could also be more cost-effective.

Weather Conditions Impact:
It's evident that users prefer the service during best or neutral weather conditions, including clear skies and misty conditions. The company should plan its service offerings and promotions around these favorable weather patterns to maximize user engagement.

Humidity and Wind Sensitivity:
Days with high humidity and strong windspeeds have a negative impact on bike usage. Offering discounts or promotions during such conditions may not be effective, as it's inconvenient for customers to commute by bike. Instead, the company should prepare for decreased demand on such days and manage resources accordingly.

Yearly Growth:
The data indicates a positive relationship between the year variable and bike rental demand. As people adapt to bike sharing, there is an expected increase in users over time. While external factors like the COVID-19 pandemic may have influenced the trend, the long-term outlook suggests a steady rise in the number of users.

Additional Considerations:
In addition to the above, the company should continuously monitor and adapt to changing market conditions. This may involve data-driven strategies such as personalized user offers, expanding service areas, and improving bike availability to meet the evolving demands of its customers. By focusing on these key areas and being responsive to market dynamics, the company can enhance its profitability and maintain a competitive edge in the bike-sharing industry.Weather Conditions Impact: It's evident that users prefer the service during best or neutral weather conditions, including clear skies and misty conditions. The company should plan its service offerings and promotions around these favorable weather patterns to maximize user engagement.

Humidity and Wind Sensitivity:
Days with high humidity and strong windspeeds have a negative impact on bike usage. Offering discounts or promotions during such conditions may not be effective, as it's inconvenient for customers to commute by bike. Instead, the company should prepare for decreased demand on such days and manage resources accordingly.

Yearly Growth:
The data indicates a positive relationship between the year variable and bike rental demand. As people adapt to bike sharing, there is an expected increase in users over time. While external factors like the COVID-19 pandemic may have influenced the trend, the long-term outlook suggests a steady rise in the number of users.

Additional Considerations:
In addition to the above, the company should continuously monitor and adapt to changing market conditions. This may involve data-driven strategies such as personalized user offers, expanding service areas, and improving bike availability to meet the evolving demands of its customers.

By focusing on these key areas and being responsive to market dynamics, the company can enhance its profitability and maintain a competitive edge in the bike-sharing industry.¶

##### Hypothesis Testing and Findings:
Null Hypothesis:
The null hypothesis assumed no relationship between the independent variables (X) and the dependent variable (Y), implying that the coefficients of the independent variables are equal to zero.

Rejection of Null Hypothesis:
The model's summary clearly indicates that all the coefficients of the independent variables are not equal to zero. Therefore, we reject the null hypothesis, signifying a statistically significant relationship between the independent variables and bike rental demand.

r2=0.847
adjusted r2 = 0.845

#### contacts
Created by Susrita Das
https://github.com/SusritaDas/BikeSharing-Assignment
Group : C55

#### Acknowledgements
Inspired by teacher Akashdeep Makkar
Notes and lectures from upgrad, Live sessions from upgrad





```python

```
