# Vaccination Model:  Seasonal Flu Vaccine


## Project Overview

This project uses phone survey data from 2009-2010 to build a machine learning model that helps a non-profit firm understand how peoples backgrounds, opinions, and health behaviors are related to their personal vaccination patterns.

## Business Problem

As COVID-19 continues to coincide with every day life, it is important to continue to educate about the positive effects of vaccinations.  As the push for vaccinations continues, it is important to remind the public of the seasonal flu vaccine.  In an effort to push for higher vaccination rate for the seasonal flu vaccine, a local non-profit is looking to understand how peoples backgrounds, opinions, and health behaviors are related to their personal vaccination patterns.  This will provide the necessary guidance for public health efforts as flue season approaches.

## The Data

In late 2009 and early 2010, the United States conducted the National 2009 H1N1 Flu Survey.  This survey was conducted through the phone and asked respondents if they had received the H1N1 and seasonal flu vaccines.  They were also asked questions about themselves.  The additional questions were to see their social, economic, and demographic background as well as opinion based questions.  The opinion based questions focused on risks of illness and vaccine effectiveness, and behaviors toward mitigating transmission.

To better utilize the data, this project focuses on just how the respondants answered the questions to the seasonal flu vaccine.


## Model
Four different models were created before choosing best one.  Before the data was modeled it was cleaned, split, and scaled.
Model Types:
* Logistic Regression
* KNN
* Random Forest
* XG Boost


## Conclusion

The model which is best fit for predicting if someone received the season flue vaccine is the logistic regression model.  It will accurately predict 78% of the time.
After modeling it is a fair assumption to say that the attributes of the home which will increase the sale price the most are as follows:
* Waterfront will increase the sale price by 39%:

![Waterfront.png](./Images/Waterfront.png)

* Homes with a grade of 11 or higher will increase the sale price of them home to that of lesser grades in the range 14% to 33%

![Grade.png](./Images/Grade.png)

* Homes which were built after 1980 will increase the sale price of the home by 21%

![Year_Built.png](./Images/Year_Built.png)


## Next Steps

The stakeholder should move forward looking to invest in homes which:
* Were built after 1980
* Are located on the water
* Have a grade of 11 or higher

This will in turn help when they resell the homes in the future. If the stakeholder is looking to add more features in their search in the future, the suggestion would be:
* Homes with multiple floors which increases the sale price by 12%
* Homes which have a view which increases sale price by 15%
