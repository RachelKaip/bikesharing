# Bike Sharing Service Analysis

## Overview of Analysis
#### What is CitiBike?
CitiBike is a bike sharing service that allow city-goers to rent bikes that they can use to get all over the city and back and back again.  There are CitiBike stations scattered throughout the city that allow users drop bikes and pick up new ones as they need.  The abundance of bikes and stations leave both tourists and locals raving about how easy CitiBikes make it to get around town.  Smelly subways?  Who needs them when you have a CitiBike!

#### Purpose of the Analysis
The purpose of this analysis is to look into the NYC CitiBike usage trends and use the findings to convince other cities to implement the service as well.  In this analysis, we are looking at three major factors: weekday usage, hourly usage, and usage by gender. 

Based on the findings below, other cities will be able to compare their deographics to NYC and see if CitiBike is right for them!  

**Tableau Public Dashboard:** https://public.tableau.com/app/profile/rachel.kaip/viz/Bikesharing_Challenge_16479942102770/CitiBikeUserStory?publish=yes

## Results 

###### Top Starting and Ending Locations

The most popular starting locations looks very similar to the top ending locations.  Thus, CitiBike looks to be most popular in Lower Manhattan where the larger commercial district is located. 

![topstarting](https://user-images.githubusercontent.com/94569240/159818999-1dee3253-fa63-4d00-b9cc-ad3e89601b48.PNG)

![topending](https://user-images.githubusercontent.com/94569240/159818976-ac007ec7-a38f-432f-9410-6e61a081ecc5.PNG)

###### Checkout Times by User

CitiBikes are consistently used for longer durrations in the morning hours as opposed to later in the day.

![checkoutbyuser](https://user-images.githubusercontent.com/94569240/159819021-833b0b7a-8999-4061-b97e-1d11584c7f18.PNG)

###### Checkout Times per Day by Hour

The most popular days/hours to use a CitiBike are consistent with those of the standard work day.  Commuters must opt for CitiBikes instead of other transportation options.

![tripsbydayperhour](https://user-images.githubusercontent.com/94569240/159819038-66f6c8ca-30ac-480e-8ee3-fd403796a73f.PNG)


###### Gender Breakdown

Of the 2,344,224 rides, the majority have been taken by our Male users.  

![gender](https://user-images.githubusercontent.com/94569240/159819050-ea5057b1-e58f-4e32-80d9-2aeb6a3d3179.PNG)

###### Checkout Times by Gender

While men are the majority of our users,  all three gender types use the bikes for a similar amount of time.

![checkoutbygender](https://user-images.githubusercontent.com/94569240/159819065-f4b3cf18-e7a7-49fb-baf8-9c693f985c0f.PNG)

###### Trips by Gender

Each gender's day and time frame usage aligns with the standard workday commuting hours.  Again, men are the most likely to rent a CityBike.

![tripsbygender](https://user-images.githubusercontent.com/94569240/159819081-857b1b10-fda0-4f97-bd25-b7dbe2e75eac.PNG)

###### User Trips

There are a more subscribers using the CitiBikes than casual customers.  Subscribers use the service during the week and customers are more likely to use the service on the weekends. 

![trips by user](https://user-images.githubusercontent.com/94569240/159819101-4777c3ef-9996-42ce-afc7-c6edc845c206.PNG)

## Summary
While one might assume that Citibikes are simply for tourists, we found that the most popular days and times to use CitBikes were consistent with the commuting hours for the standard work-week.  To further strengthen this theory, the last visualization above proves that the majority of CitiBike users are subscribers as opposed to customers.  It is safe to assume that tourists would not subscribe to a service they could only use on vacation, unlike residents who are able to use the service daily.  Thus, you do not need to be a tourist destination to have a successful CitiBike service.  Any city with a high population of resident commuters may benefit from a service like this.

Also, Cities that have a larger male population may also have a successful CitiBike service thank those without as the data above shows that most of NYC's citi bike users were male.  

Lastly, there are two additional visualizations I reccomend looking at given this data set:  
1. A map and bar graph of the top starting and ending points' popularity per hour/weekday.  This may help us better understand where our users are going and when- is it to work, to sight seeing destinations, or both?  
2. I would also make a line graph that shows ti difference between a customer's average trip duration and a subscriber's.  This may help us understand how long of a trip it takes for someoen to consider the subscription worth it.   
