# PyBer_Analysis
python week 5
# PyBer Analysis
An analysis of ride-share data using Python with Pandas and Matplotlib.
## Overview of PyBer_Audit:

After getting hired on with PyBer a ride-sharing app company, we were asked to work alongside our manager Omar to analyze all the rideshare data in 2019 from January to May. In the end we made a presentation to the CEO V. Isualize. She was extremely impressed with the presentation and has asked you to a new analysis showing the ride-sharing data by city. Then using Matplotlib present a graph that showing the relationship between each city type and by fare. This will help show how access and affordability differ between each type and how PyBer can improve the disparities. 
After working with the Maria and the school board to look at the academic grades in reading and math versus funding across the district, discrepancies were discovered. The analysis showed that Thomas High School has been lying about the 9th grade class scores in math and reading. After discussing with the school board, they wanted us to change the altered math and reading scores and re-run the analysis.
#### The below pseudocode provided us an outline for the analysis: 

1.	The data we need to retrieve.
2.	The merging of the city_data and ride_data into a single dataset pyber_data_df.
3.	The summary Dataframe.
4.	The total rides by city type.
5.	The total drivers by city type.
6.	The total amount of fare by city type.
7.	Average fare per ride.
8.	Average fare by driver.
9.	Created a new Dataframe based on the: “Total Rides”, “Total Drivers”,  "Total Fares", "Average Fare per Ride”, and "Average Fare per Driver".
10.	Cleaned the Dataframe.
11.	Reset the index and created a pivot table.
12.	Created a multiline plot for total fare by city type based on fare and month.

### PyBer_Analysis Results:
1.	Total rides by city. 
As you can see urban rides were significantly more frequent than Suburban or rural numbers at 1,625.
##### ![alttext]( https://github.com/mbehr11/PyBer_Analysis/blob/main/Resources/Total_rides_by_city.PNG) #####

2.	Total drivers by city type. 
From this set of data, we can see that the Urban areas request more rides means that more drivers are hanging around those areas as they have more chances of someone requesting a ride with those numbers at 2,405.

#####![alttext](https://github.com/mbehr11/PyBer_Analysis/blob/main/Resources/Total_drivers_by_city.PNG) #####

3.	Average fare by driver. 
This had a very interesting outcome because when you divide the total fare by city and the total drivers by city, the average fare goes up by almost double than the average fare numbers due to the number of drivers in the different areas. For instance, if you compare rural fares by ride and rural fate by driver it goes from $34 to $55. 
##### ![alttext](https://github.com/mbehr11/PyBer_Analysis/blob/main/Resources/Avg_fare_by_ride.PNG) #####

##### ![alttext](https://github.com/mbehr11/PyBer_Analysis/blob/main/Resources/Avg_fare_by_driver.PNG) #####

4.	Created a new Dataframe looking at the weekly fares by type of city. 

##### ![alttext](https://github.com/mbehr11/PyBer_Analysis/blob/main/Resources/Weekly_fare.PNG) #####

5.	Created a plot of the total fare by city type. As we can see urban by far had the highest fares with frequent peaks in price verses suburban or rural who had a steady line with little fluctuation in price. 

##### ![alttext](https://github.com/mbehr11/PyBer_Analysis/blob/main/analysis/Challenge_fare_summary.png) #####


## PyBer Analysis Summary:
After my analysis there are several ways to help improve disparities between city type. I would start by moving around the drivers or hiring more drivers to work in the rural, and suburban areas. Then, I would decrease the price in those areas to begin with offering deals during peak hours or credits to earn money off every time they ride. Then when ride numbers go up, increase prices to incentivize drivers to work more. Lastly, work with the city and local businesses to encourage advertising and marketing for you during big events.

I would have like to tie in driver data to see if there were more in less drivers during peak times and how much was charged over the week.
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
