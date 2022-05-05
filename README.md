# Bikesharing

## Overview/Purpose
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.

This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:
* Deliverable 1: Change Trip Duration to a Datetime Format
* Deliverable 2: Create Visualizations for the Trip Analysis
* Deliverable 3: Create a Story and Report for the Final Presentation

## Results

### Basic Information
This is the first page of the story which is dashboard, and it contains basic information about the data set. It gives details of the dataset to understand what kind of data we will be dealing with in the further analysis.

![1](https://user-images.githubusercontent.com/94920551/166932721-ee8a0db7-b41f-4f3a-a950-41e91880abd9.png)

The page contains the following information:

* Type of business (CitiBike), location with particular time frame of the data (New York City, August 2019).
* Number of the total rides: 2,344,224.
* Customer type: subscribers and customers.
* Peak hours, divided by gender which shows the user behavior.

### Checkout Times for Users
![1](https://user-images.githubusercontent.com/94920551/166932904-9e110604-9402-4638-8078-b3f20b07b273.png)

* This visualization shows the length of time for every bike ride during the month of August in 2019.
* It shows that riders typically like to ride bike between 2 and 15 minutes.

### Check Out Time by Gender
![1](https://user-images.githubusercontent.com/94920551/166933107-2e824ca5-c2a8-4acf-9e26-d12eb97dda86.png)

The graph shows number of checkout bikes and trip duration.
Three different colors represent the classification of gender. Yellow represents male, blue represents female and red represents the unknown gender.
This visualization shows the breakdown of riders by gender and duration of times showing that most of the users are men.

### Trips by weekday per Hour
![1](https://user-images.githubusercontent.com/94920551/166933365-6b0bd003-9b12-4757-b238-8f18be3360ad.png)
* The graph shows number of trips per hour and per weekday.
* The graph has hours as rows and weekdays as columns.
* The color indicates the number of trips.
* Darker shade color indicates more trips,
* Lighter shade color indicates less trips.
* Form the graph we can see that the busiest times are in the morning hours on weekdays from 6 am and 9 am and evening hours on weekdays between 5 pm and 7 pm.
* On weekends (Saturday and Sunday) the busiest times are in the middle of the day between 10 am and 6 pm.

### Trips by Gender (Weekday per Hour)
![1](https://user-images.githubusercontent.com/94920551/166933605-f8dfa31a-b891-4830-ac6e-8cc5a7ba76fc.png)
* The graph shows number of trips per hour and per weekday.
* The graph has hours on the rows and weekdays on the columns.
* The color indicates the number of the trips.
      * Darker shade color indicates more trips,
      * Lighter shade color indicates less trips.
* Additionally, the graph is divided by gender (male, female and unknown).
* From the graph we can see that distribution of the checkout times for all genders is similar.
* The busiest times are
      * In the morning hours on weekdays from 6 am and 9 am
      * In the evening hours on weekdays between 5 pm and 7 pm.
      * On weekends (Saturday and Sunday) the busiest times are in the middle of the day between 10 am and 6 pm.
* However, males have significant higher number of trips than female or unknown gender.

### User Trips by Gender by Weekday
![1](https://user-images.githubusercontent.com/94920551/166934043-4ffb0d79-a4ef-4884-beb3-d0478107b4bc.png)

* The graph shows number of trips by weekday, by user type (subscribers and customers) and by gender.
* The graph has weekdays and user type as rows and gender as columns.
* Amongst subscribers, male has the highest number of the trips especially on Thursdays and Fridays, followed by trips on Monday and Tuesdays.
* Female has similar distribution of trips, with significant lower number of trips than male.
* Unknown gender has uniform distribution of the trips throughout the week.
* Looking at the customers data we can see significant less trips throughout all genders with slight increase amongst unknown gender on Saturdays and Sundays.

### Top Starting Locations & Top Ending Locations
![1](https://user-images.githubusercontent.com/94920551/166934447-8a19b11b-bb80-47ab-b3b0-1b86e888caf7.png) ![1](https://user-images.githubusercontent.com/94920551/166934521-03b001ea-a2bf-48bf-91df-58b96e7c4ad0.png)


* With the help of these two graphs we can see the most popular starting and ending locations.
* The color indicates the types of users
          * Orange color represent subscribers,
          * Blue represent customers.
* The bubble shapes represent the number of trips.
* Larger bubbles represent locations with the highest number of trips,
* Smaller bubbles represent lowest number of trips.
* Also, we can find out popularity of stations amongst subscribers vs. customers and what areas are more popular than others.
* Downtown area is much more popular than other areas, yet it is as important for surrounding areas to have bike services for good customer experience.

## Summary

