# bikesharing

## Project Overview
The purpose of this project is to create a story of data visualizations and analysis utilizing Tableau using the data from a New York City bike-sharing business in order to pitch a start-up of a similar bike-sharing business for the city of Des Moines, Iowa.

## Results
Using Tableau, a series of data visualizations are created from the data analysis in order to convey the information in an easy-to-digest manner.  These visualizations are collected and presented in a Tableau story at [NYC Citibike Story](https://public.tableau.com/app/profile/michelle5662/viz/NYCCitibikeStory_16633398931420/NYCCitibikeStory?publish=yes). There are seven charts that show the story the New York City citybike data tells.

### Checkout Times for Users

![Checkout_Times_for_Users](https://github.com/mewers2/bikesharing/blob/main/Resources/Checkout_Times_for_Users.png)

The majority of bikes are checked out for use for 30 minutes or less.  This chart also provides the capability to chart just certain hours of the day for a deeper dive into the timing usage.

### Checkout Times by Gender

![Checkout_Times_by_Gender](https://github.com/mewers2/bikesharing/blob/main/Resources/Checkout_Times_by_Gender.png)

This chart has great flexibility for customization with the filtering options.  The main message displayed says that males are using most bikes and most commonly, the duration of each ride lasts under 30 minutes.

### Trips by Weekday per Hour

![Trips_by_Weekday_per_Hour](https://github.com/mewers2/bikesharing/blob/main/Resources/Trips_by_Weekday_per_Hour.png)

This chart uncovers the main usage times of day, or "rush hour" for NYC citibikes.  Wednesday evening is the lightest weekday "rush hour" timeframe for bike rentals. Saturdays show moderate usage from 10am to 7pm and Sundays show mild usage in a similar time window.

### Trips by Gender (Weekday per Hour)

![Trips_by_Gender](https://github.com/mewers2/bikesharing/blob/main/Resources/Trips_by_Gender.png)

For the most part, males are using the bikes 6am to 9am and 4pm to 7pm on weekdays.  Females' utilization shows a faint similar trend, but to a much lesser degree.  Wednesday evening is the lightest weekday "rush hour" timeframe for bike rentals. 

### User Trips by Gender by Weekday

![User_Trips_by_Gender_by_Weekday](https://github.com/mewers2/bikesharing/blob/main/Resources/User_Trips_by_Gender_by_Weekday.png)

This heatmap displays that the overwhelming majority of user trips are made by male subscribers and specifically Thursday is the most popular day for those rentals.

### Average Trip Duration

![Average_Trip_Duration](https://github.com/mewers2/bikesharing/blob/main/Resources/Average_Trip_Duration.png)

The average trip duration graph displays the average length of a trip based on the customer's birth year.  Minus some outliers, the general trend displayed by this graph is that the younger the customer, the longer the trip.

### Bike Utilization

![Bike_Utilization](https://github.com/mewers2/bikesharing/blob/main/Resources/Bike_Utilization.png)

The bike utilization chart displays how much each individual bike is being used, which can be indicative of which bikes might need more maintenance.  This chart indicates that the usage is mostly uniform across the fleet of citibikes at roughly 300,00 seconds or approximately 83 hours, with about 10% of the bikes taking the lion share of the bike rides ranging from 1.5M seconds (415 hours) to 3.8M seconds (1,000 hours).

## Summary
The citibike business seems to be a favorable opportunity based on the NYC data.  The majority of utilization takes place during the weekdays while people travel to and from work. If Des Moines has a large population that lives close enough to their office to bike, this business could translate well into the Des Moines, Iowa market.

One additional visualization I would perform with the given dataset is to first calculate the distance from the start point to the end point for each bike rental, then chart the distance traveled for each rental on a bar chart.  This new chart will help to understand how often the bikes are rented and returned in the same location versus relocated before being returned.  It will also provide an opportunity to glean further insights about the purpose for which users are renting the bikes.  
The next visualization I would perform is to graph the distance traveled by age.
Lastly, I would chart the distance traveled by user type, perhaps with a heatmap.