
# NYC Citi Bike Analysis
Tableau Public:
[link to NYC Citi Bike Story](https://public.tableau.com/app/profile/ning.yang/viz/NYC_CitiBike_Challenge_16546215103060/NYCCitiBikeStory?publish=yes)
## <font color=#6495ED>Overview of Project</font>
We were impressed by the bike share program when we visited New York city.  We are planning to start a similar business for home town. The mechanics of making this business work might be different. We decide to figure out how the bike share business actually works in New York city. 
### <font color=#6495D>Purposes</font>

1. Read in  data file 201908-citibike-tripdata.csv. Use Python and Pandas functions to convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). Then export the DataFrame as a CSV file

2. With Tableau we will create a story with our analysis visualizations that show

- Top starting location
- Top ending location
- Checkout time for users
- Checkout time by gender
- Trips by weekday for each hour
- Trips by gender by weekday per hour
- User trips by gender by weekday

---
## <font color=#6495ED>Resources</font>
* Data Source: 
201908-citibike-tripdata.csv data file from [NYC CiTiBike](https://ride.citibikenyc.com/system-data)
    
* Software: 
    * Jupyter notebook
    * Tableau desktop public    


## <font color=#6495ED>Results</font>
-  The most popular start location was Pershing Square [40.7519, -73.9777] with 16,564 rides.

!["Top_Starting_location"](https://github.com/NingYang2022/NYC_Citi_Bike_Analysis/blob/main/images/Top_Starting_location.png?raw=true)

- The most popular ending location was Pershing Square [40.7519, -73.9777] with 16,455 rides.

!["top_ending_location"](https://github.com/NingYang2022/NYC_Citi_Bike_Analysis/blob/main/images/top_ending_location.png?raw=true)

- Trip duration at 5 minutes had the most rides with 146,752 based on the Checkout_time_for_users graph.

!["checkout_time_for_users"](https://github.com/NingYang2022/NYC_Citi_Bike_Analysis/blob/main/images/checkout_time_for_users.png?raw=true)

- Males trip duration at 5 minutes had the most rides with 108,087. Females trip duration at 6 minutes had the most rides with 34,151. For Unknown, the trip duration at 11 minutes had the most rides with 7,389.

!["checkout_time_by_gender"](https://github.com/NingYang2022/NYC_Citi_Bike_Analysis/blob/main/images/checkout_time_by_gender.png?raw=true)

- 6:00pm on Thursdays are the most popular start time with 44,905 rides. The least popular start time are Tuesdays at 3:00am with 360 rides 
based on the heat map.

!["trips_by_weekday_for_each_hour"](https://github.com/NingYang2022/NYC_Citi_Bike_Analysis/blob/main/images/trips_by_weekday_for_each_hour.png?raw=true)

- Females most often start at 6:00pm on Thursdays with 11,336 rides, and least likley to start  on Tuesday 3:00am with 41 rides, 
Males most often start at 6:00pm on Thursday with 30,749 rides. and least often start on Tuesday 3:00am with 277 rides, based on the heat map.

!["trips_by_gender_weekday_per_hour"](https://github.com/NingYang2022/NYC_Citi_Bike_Analysis/blob/main/images/trips_by_gender_weekday_per_hour.png?raw=true)

- Thursday for subscribers is the most popular day for trips. Subscribers are more likley to have a trip than regular customers. Male subscribers are more likley to ride then females.

!["user_trips_by_gender_by_weekday"](https://github.com/NingYang2022/NYC_Citi_Bike_Analysis/blob/main/images/user_trips_by_gender_by_weekday.png?raw=true)

## <font color=#6495ED>Summary</font>
According to the results, we can see that males have more rides than females; Subscribers account for more rides than regular customers; 6:0pm on Thursdays is the most popular time for rides.

Two additional visualizations are suggested for future analysis

- The bikes used the longest will probably be the ones that require the most maintenance, so we'll need to determine which bikeid have the highest sum of "Tripduration."

- We will import more csv data files for other months and compare the trip rides across the whole year.






