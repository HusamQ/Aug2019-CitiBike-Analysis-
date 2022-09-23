# August 2019 CitiBike Analysis with Tableau
Module 14 Challenge. 

# Overview of the project:
Using Tableau and Pandas, this analysis to support the business proposal given the stakeholders to invest in a Bikesharing service in Des Moines, Iowa. 
[Here is the Tableau dashboard](https://public.tableau.com/app/profile/qarawih/viz/Aug2019CitiBikeAnalysis/Checkouttimeforusers?publish=yes)

# Data source:
I used the Citibike s3 bucket tripdata for New York City for August 2019. The CSV file has more than 2 million trip records. 
There are two different type of users: Subscribers and Customers, Male and Female. 

![Customer Type](https://github.com/HusamQ/Aug2019-CitiBike-Analysis-/blob/eacb7a64a702119fc51e987c8e150cc5127c4a69/Images/usertype.PNG)

![By Gender](https://github.com/HusamQ/Aug2019-CitiBike-Analysis-/blob/2747fe90126d1ad5650bf53d90b2f7644689d64a/Images/Riders-ByGender.PNG)
 
#  Checkout Times for Users:

In this graph it shows the length of time that bikes are checked out for all riders. It appears that majority of Riders use the bike for at least the first 20 minutes.
![Checkout](https://github.com/HusamQ/Aug2019-CitiBike-Analysis-/blob/1916c7ea46c91f75beeb78b275f59d20ccf40eb8/Images/Checkout-timefor-user.PNG)

# Checkout Times by Gender:
This graph shows the length of time that bikes are checked out for each gender. Comparing to women, mostly men rider rent the most for the first hour.
![Checkout By Gender](https://github.com/HusamQ/Aug2019-CitiBike-Analysis-/blob/1916c7ea46c91f75beeb78b275f59d20ccf40eb8/Images/CheckOutByGender.PNG)

# Trips by Weekday for Each Hour 
 A heatmap graph to show the number of bike trips by weekday for each hour of the day.
 ![Weekday Heat Map](https://github.com/HusamQ/Aug2019-CitiBike-Analysis-/blob/1916c7ea46c91f75beeb78b275f59d20ccf40eb8/Images/Heatmap-Byhour.PNG)
 
 # Trips by Gender for Weekday per Hour:
 A heatmap to graph the number of bike trips by gender for each hour of each day of the week.
 ![Weekday Heat Map By Gender](https://github.com/HusamQ/Aug2019-CitiBike-Analysis-/blob/1916c7ea46c91f75beeb78b275f59d20ccf40eb8/Images/TripsbyWeekdayperHour.PNG)
 
 # Trips by Gender by Weekday:
 A heatmap that shows the number of bike trips broken down by gender for each day of the week by each Usertype: 
  ![Weekday Heat Map By Gender by Usertype](https://github.com/HusamQ/Aug2019-CitiBike-Analysis-/blob/1916c7ea46c91f75beeb78b275f59d20ccf40eb8/Images/Gender.PNG)
  
# Summary of Analysis:

Based on the data that we analyze for August 2019, by looking at everyday trip data the majority of citibike riders are male comparing to all the time from morning to through the week. Although, there's an increase of female bike riders starting to increase in the evening and especially on the weekend, men customers and subscribers are still dominant.

# Suggested additional visualization: 

- I would suggest to visulize the bike rider data based on the Geo location where the trip starts and where it ends. Doing so will allow us to have further insights about locations and the number of bikes were available in that area. 

- Another suggestion would be visualizing trip data by focusing on the age of the riders. To let us know the demographic of the customers. This provide more info for other services that might be introduced now or in the future, or market for the least age riders to convince them to use the service.
  




