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

* Basic Information
This is the first page of the story which is dashboard, and it contains basic information about the data set. It gives details of the dataset to understand what kind of data we will be dealing with in the further analysis.

![1](https://user-images.githubusercontent.com/94920551/166932721-ee8a0db7-b41f-4f3a-a950-41e91880abd9.png)

The page contains the following information:

* Type of business (CitiBike), location with particular time frame of the data (New York City, August 2019).
* Number of the total rides: 2,344,224.
* Customer type: subscribers and customers.
* Peak hours, divided by gender which shows the user behavior.

* Checkout Times for Users
![1](https://user-images.githubusercontent.com/94920551/166932904-9e110604-9402-4638-8078-b3f20b07b273.png)

* This visualization shows the length of time for every bike ride during the month of August in 2019.
* It shows that riders typically like to ride bike between 2 and 15 minutes.

* Check Out Time by Gender
![1](https://user-images.githubusercontent.com/94920551/166933107-2e824ca5-c2a8-4acf-9e26-d12eb97dda86.png)

The graph shows number of checkout bikes and trip duration.
Three different colors represent the classification of gender. Yellow represents male, blue represents female and red represents the unknown gender.
This visualization shows the breakdown of riders by gender and duration of times showing that most of the users are men.

* Trips by weekday per Hour
![1](https://user-images.githubusercontent.com/94920551/166933365-6b0bd003-9b12-4757-b238-8f18be3360ad.png)
* The graph shows number of trips per hour and per weekday.
* The graph has hours as rows and weekdays as columns.
* The color indicates the number of trips.
* Darker shade color indicates more trips,
* Lighter shade color indicates less trips.
* Form the graph we can see that the busiest times are in the morning hours on weekdays from 6 am and 9 am and evening hours on weekdays between 5 pm and 7 pm.
* On weekends (Saturday and Sunday) the busiest times are in the middle of the day between 10 am and 6 pm.


## Summary
