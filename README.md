# Bike-Sharing

## Project Overview
This project involves using Tableau to analyze and visualize some bike-sharing app data. Using real data from CitiBike, a bike-sharing system for New York City, we can predict how successful a company might be in another city. 

## Results
Check out my [Tableau Public Story](https://public.tableau.com/app/profile/alex.deans.gravlee/viz/NYC_Citibike_Challenge_16408098850940/NYCStory?publish=yes) for the visualizations. 


### Page 1
This map highlights popularity of starting location, that is, where riders check out a bike from. Bikes are more likely to be checked out in Manhattan, and less likely in Brooklyn or Queens. This can be due to a difference in the number of tourists, population density, and/or rider demographics as it relates to vehicle ownership and daily commuting styles. 

### Page 2
This graph shows how many bikes are checked out based on the duration of their ride (filtered to show anything less than three hours). We can see that most bikes are checked out for about five minutes, and the number of bikes used for more than 30 minutes drops drastically, with very few bikes being used for more than an hour. 

### Page 3
Here we have two visualizations. The first shows a breakdown of our previous graph based on the gender of the rider, and the second is a pie chart of the ratio of riders based on their gender. Given that male riders make up the majority of the riders in this data, the line graph for male riders is very close to the one on the previous slide. 

### Page 4
Again we have two visualizations - both showing show the busiest hours for bike rentals based on days of the week. The top heatmap shows this for all riders, and the bottom heatmaps are broken down by gender. Darker segments show more trips during that hour, and lighter segments show fewer trips. Based on these heatmaps, we can see an increase of riders 7-9 am and 5-7 pm on weekdays, likely for commuting to and from work or school. Saturdays riders are more likely to rent a bike between 10 and 5, with no major peaks by hour within that range. Again, due to male riders contributing to most of our data, the heatmap for male riders is most similar to the overall rider heatmap.

### Page 5
Our last heatmap shows subscriber status and gender. Male riders make up the majority of subscribers, and subscribers make up the majority of Citibike rentals in NYC. There does not seem to be a significant correlation with day of the week based on subscriber status. 


## Summary
Based on all of these results, we can see the overall trends in bike-sharing app usage in New York City. Most of the users are male, making up the majority of subscribers and total rides. Many rides take place during the typical morning and evening commutes Monday through Friday, with rides on Saturday spread throughout the day. 

### Future Considerations
Another analysis we could perform with this data is looking at the average distance traveled, or distance traveled based on time of day. We can also examine the total distance a given bike would have traveled, as opposed to merely the time the bike is checked out. If a bike is being used for a large portion of time, but is not moving for a portion of that, we do not have a strong indicator of bike usage to help determine the necessary maintenance. By using distance instead (as a function of the distance between the starting and ending station locations), we can get a better indication of each bike's usage. 

With more data, we could incorporate a profit analysis based on the fee each rider is paying, and determine the most profitable hours. When launching a bike-sharing app in a new city, we could base on fees on which hours may get more or less usage, which can also help incentivize riders to sign up for a subscription. 


