# bikesharing
## Overview of Project

https://public.tableau.com/profile/jose.santos4967#!/vizhome/Module14Challenge_16205284163930/Bike_Sharing?publish=yes

![](Slide1-intro.PNG).

### Purpose

The purpose of this analysis was to demonstrate that based on NYC bike sharing data, a similar business in Des Moines would likely succeed.

## Results

### Trip Duration

A plot of the number of bike trips tkane versus duration, shows that the majority of the trips are short:  Almost all are shorter than 60 minutes, and the most typical duration is less than 10 minutes:

![](Slide2-Trip_duration.PNG)

A plot descriminating the trip duration by gender of the rider shows that 
1. Every gender uses bike sharing.
2. The number of male riders is ~ 3x that of female riders.
3. The distribution of the trip duration does not change signicantly depending on the gender of the rider.

![](Slide3-Trip_duration_by_gender.PNG)

A plot that shows the number of bikes shared per starting and ending time per weekday shows that there are clear peak usage times:
1. From Monday to Friday the peak hours are 7 to 9 AM and 4 to 7 PM.
2. During the weekends,the peak hours are between 9 AM and 6 PM - and there appear to be more people riding the bikes on Saturday than Sunday.

![](Slide4-Slide4-Peak_usage.PNG)

![](Slide5-Peak_usage_gender.PNG)

![](Slide6-Gender_weekday.PNG)

![](Slide7-Starting_Location.PNG)

![](Slide8-Ending_Location.PNG)

When the webpage loads, the unfiltered page shows all of the sightings:
![](static/images/unfiltered_table.PNG).

Filtering the data by the city "el cajon" by entering "el cajon" in the "enter city field" and pressing enter produces the filtered table:
![](static/images/filtered_on_city.PNG)

Filtering on date (01/13/2010) produced the filtered table:
![](static/images/filtered_on_date.PNG)

If we then add an additional filter to the date, by entering "pa" in the "enter state" field, we obtain the following filtered table:
![](static/images/filtered_on_date_and_on_state.PNG)

## Summary

### Drawbacks of current webpage
One drawback of the current design of this webpage is that it does not have a reset button to remove all filters and show the initial unfiltered table.

### Suggested Additional developments
The following additional developments would really help to improve the user interface:
1. The implementation of a reset button that when pressed would remove all the filters AND show the unfiltered data again.
2. Whenever the sighting had a photograph, it would be great to be able to add it so that viewers could see it.
