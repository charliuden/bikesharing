
# Bikesharing

Would a bike-sharing business in Des Moines be successful?

## Overview of the analysis:

The goal of this analysis is to determine whether a bike share business would be successful in Des Moines, Iowa. There are many things to consider before investing in a bike-share business. For example, what public transport is already available and is it affordable? We have chosen to look at the performance of a bike sharing business in another city: Citi Bikes, located in New York City. 

Citi Bike user data is freely available on their website. The dataset includes information on the rider (ie. date of birth and gender), as well as the ride itself (ride length, and start and stop locations) for every month since 2013. 

To aid in understand the potential success of a bike share business in Des Moines, we aim to use Citi Bike data from August 2019 to answer the following questions:

1. Where in NYC are bikes being used most?
    a. Where are bike ride start locations?
    b. Where are bike ride stop locations?
2. How long are bikes checked out for and is there a difference in use between genders?
3. When are bikes being used most frequently and is there a difference in use between genders?
4. Is user type (subscriber versus customer) changing with gender and time of day?

We chose August because a month with fair weather should see the more frequent bike use and therefore provide the most data on users and bike rides. 
                                         
## Results:

Tableau was used to display this data. Visuals and descriptions of the results can be found in the following Tableau story board: [link to Tableau dashboard](https://public.tableau.com/app/profile/charlotte.uden/viz/NYCCitiBikeAnalysis_16406310706280/NYCCitiBikeAnalysis?publish=yes)

## Summary:

1. Where in NYC are bikes being used most?

Analysis of start and end locations indicates that bikes trips start and end most frequently in southern Manhattan. Either this is becuase of tourist use or use by commuters who live in the city. 

2. How long are bikes checked out for and is there a difference in use between genders?

The mode trip duration is 5 hours. Very few people check out a bike for less than an hour. Beyond a 5 hour check out time, the frequency of use gradually decreases. Breaking the data up by gender reveals that, mode trip duration is 1 hour longer for women. However, the plot provided does not show where these longer trips are occurring and whether the users are subscribers or customers. 

3. When are bikes being used most frequently and is there a difference in use between genders?

Temporal patterns in use do not differ drastically between genders. Bike use goes up on weekends and during week day commuter hours. The plots provided display that there is little difference in fluctuations in use time between genders. 

4. Is user type (subscriber versus customer) changing with gender and time of day?

The final plot provided begins to tackle the reason for use that previous plots do not. It is clear form this plot that short term customer use goes up on weekends. Long term subscriber use increases on week days. This indicates that tourists are using the bikes on weekends while NYC residents tend to use the bikes to commute to work. Again, there is no difference in patterns of use between males and females, only that more males use the bikes than females. 

This analysis has revealed the where and the when. However, further investigation into user type would further our understanding if Citi Bike use. To get a clearer picture of use by tourists versus commuters, I suggest a comparison of two maps. The first map would show bike count by point size filtered for customers only and second would show bike count by point size filtered for subscribers only. 

A second visual that may tease out patterns in user type would be to again map bike start (or stop) locations, this time matching point size to mean trip duration. Being able to filter and toggle between user type might get at short commuter rides by subscribers versus long rides by tourists. 







