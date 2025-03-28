# Introduction
## Background
ACLO, one of the largest student sports accosiation in Groningen, Netherlands, currently has more than 19,000 cardholders.
With a regular card, a cardholder can make use of group lessons, courses and open hours. A cardholder who wants to use the fitness in the Sports Centre in addition to the regular sports offer, must purchase a Fitness Card, in addition to the regular card. The percentage of cardholders who have a Fitness Card is relatively low. 

## Goal
To increase the number of fitness users and other ways to promote the Fitness Card. For example, since August 31, 2020, it is possible to use the fitness in the weekends and university holidays with only a regular ACLO card.

## Challenge
Based on the use of the Fitness, predict the number of visitors to the Fitness, taking into account the influence of 
1.  Seasons
2.  Holidays
3.  The day of the week
4.  Gender
5.  Educational institution (Hanze vs. UG)
6.  Exam periods for the UG students.

## Data Resource
The ACLO data is directly provided by ACLO


The covid lockdown period in Netherlands is according to this graph
https://www.researchgate.net/publication/363421335/figure/fig1/AS:11431281083759590@1662772038959/Timeline-of-COVID-19-restrictions-in-the-Netherlands-from-April-2020-to-April-2022.png

Zijlmans, J., Tieskens, J. M., van Oers, H. A., Alrouh, H., Luijten, M. A., de Groot, R., ... & Polderman, T. J. (2023). The effects of COVID‐19 on child mental health: Biannual assessments up to April 2022 in a clinical and two general population samples. JCPP advances, 3(2), e12150.


As for the weather data, it's from this database:

## Model Evaluation
In this following project, we will adopt these measuring matrixes
1.  Mean Absolute Error:
    The average absolute difference between predicted and actual values, less sensitive to outliers
2.  Mean Squared Error: 
    The average squared difference between predicted and actual values, sensitive to outliers
3.  R-squared:
    The proportion of the variance in y that is predictable from x
4.  Adjusted R-squared: 
    Modifies the R-squared value based on the number of predictors and the sample size.
