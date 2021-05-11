# bikesharing
## Overview of Project

https://public.tableau.com/profile/jose.santos4967#!/vizhome/Module14Challenge_16205284163930/Bike_Sharing?publish=yes


### Purpose

The purpose of this analysis was to demonstrate that based on NYC bike sharing data, a similar business in Des Moines would likely succeed.
The complete presentation can be viewed [here](https://public.tableau.com/profile/jose.santos4967#!/vizhome/Module14Challenge_16205284163930/Bike_Sharing?publish=yes).

## Results

### Trip Duration

A plot of the number of bike trips taken versus trip duration, shows that the majority of the trips are short:  Almost all are shorter than 60 minutes, and the most typical duration is less than 10 minutes:

![](Slide2-Trip_duration.PNG)

A plot descriminating the trip duration by gender of the rider shows that:
1. Every gender uses bike sharing.
2. The number of male riders is ~ 3x that of female riders.
3. The distribution of the trip duration does not change signicantly depending on the gender of the rider.

![](Slide3-Trip_duration_by_gender.PNG)

A plot that shows the number of bikes shared per starting and ending time per weekday shows that there are clear peak usage times:
1. From Monday to Friday the peak hours are 7 to 9 AM and 4 to 7 PM.
2. During the weekends,the peak hours are between 9 AM and 6 PM - and there appear to be more people riding the bikes on Saturday than Sunday.

![](Slide4-Peak_usage.PNG)

A plot that breaks down day usage by gender and per customer type (subscriber versus non-subscriber) shows that:
1) The number of male and female subscriber users is significantly larger than those users that are non-subscribers.
2) The number of unknown gender riders that are non-subscribers is larger than those that subscribe the service.
3) There is no clear prefered work weekday to rent a bike for non-subscribers of all genders - usage is low on all days.
4) The preference to rent bikes during the work week is stronger among males than females - Thursday being a peak day for male subscriber usage.

![](Slide5-Peak_usage_gender.PNG)

When the start and ending ride times are plotted by gender per weekday, it is clear that there are peak usage times and days for female and male riders but not by those with gender unknown:
1. Males and females peak weekday ride hours are between 7AM to 9AM and 4 to 7PM.
2. On the weekends, all genders share the same peak usage hours between 9 AM and 7 PM.

![](Slide6-Gender_weekday.PNG)

Plotting the start location of a bike ride by gender on the map of New York city shows that there are "hotspots" to pick up a bike and start riding.

Interestingly, the preference for the starting location is not perfectly aligned by gender: in some starting locations the number of female and male riders is almost the same while in others there is a clear preference for male riders.  

The preferred starting location for those of "unknown" gender can not be deciphered likely due to the small number of uknown gender riders compared to male and female riders. 

![](Slide7-Starting_Location.PNG)

Plotting the end location of a bike ride by gender on the map of New York city shows that there are "hotspots" to drop off a bike.

As observed for the preferred locations to pick up a bike, the preference for the ending location is not perfectly aligned by gender: in some locations the number of female and male riders is almost the same while in others there is a clear preference for male riders.  

Unlike in the plot for the starting locations, there appear to be favorite spots to drop off a bike on the west side of the city, across the river Hudson.

![](Slide8-Ending_Location.PNG)


## Summary

### Overall Analysis
The key take ways from this analysis are:
1. All genders ride rental bikes suggesting a large customer base for a ride sharing business.
2. There are clear peak times for bike usage - these seem to overlap with morning hours before work and afternoon hours after work suggesting that some of the riders may use the bycicles to get to and from work.  If this is the case, then non-peak hours could be advertised for tourist usage thereby increasing revenue.
3. The average ride is short suggesting that the business may not need a large number of bikes to satisfy all the riders needs within the city - an analysis of directional flux would be important to determine if there is a large number of riders taking the same trips (start location to end location).

### Suggested Additional Data analysis for NYC Bike Sharing 
The following additional analysis would help make the business proposal clearer:
1. A plot that shows the preferred start locations by hour of the day per day of the week.
2. A plot that shows the preferred end locations by hour of the day per day of the week.


### Suggested Additional Data gathering for Des Moines versus NYC
The following additional information would help predict if the NYC analysis is a good basis to evaluate the success of a bike sharing business in Des Moines:
1. The population of Des Moines that lives and/or works in the city compared to the same number in NYC.
2. The number of tourists that visit Des Moines versus those that visit New York City.  
