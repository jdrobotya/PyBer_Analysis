## PyBer Analysis

### Overview of the analysis:
The purpose of this analysis  is to visualize with multiple line graph the total weekly fares for Urban, Suburban and Rural city types. First, I  combined two data sets  - city data and ride data. Then I used the 'group by()' function to find total rides, total drivers  and total amount of fares for each city type.I stored data in a Data Frame and then formatted columns. I get the total fares for each type of city by the date by creating a pivot table with the 'date' as the index, the columns ='type', and values='fare'. I created a new DataFrame which reflects only rides from January to April and resampled data to get the sum of the fares for each week.

### Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
When I did an overall analysis for drivers, fares and rides for all city types, Urban city had the most  drivers, rides and the highest total fare. Rural city drivers had the lowest numbers for these three categories. Suburban was in  the middle in terms of total drivers, riders and fares. 

Despite the high total numbers, Urban city drivers get  the lowest  average fare per rider and  driver.  Suburban city drivers are still in the middle, and Rural city drivers get the highest average fare per rider and  driver.

![Screen Shot 2022-05-22 at 7 46 51 PM](https://user-images.githubusercontent.com/103322251/169721269-1fd66423-da39-440e-9b78-a78bc5d4583b.png)

When I shrinked the data to the weekly fare for each city type for the rides provided from January to April, The total fare for Urban city drivers was the highest. Suburban was in the middle and Rural was in the bottom of the graph with the lowest total fares. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/103322251/169721873-204f6e7a-4216-44e0-b5dd-d9ed04cf0769.png)

### Summary: three business recommendations to the CEO for addressing any disparities among the city types.
1. Since  urban trips are shorter than rural, it would make sense to increase the fare based on the specific day time. For example, in the morning/evening , when everyone is in a rush to get to/out of  work/school etc. 
2. I'd recommend  moving more drivers to provide Suburban trips if there is a demand.  The trips will be  a little bit longer, but the fare will be higher and there will be less turnover of riders. As the graph shows, the best month to do that change will be Apriil. Suburban fare starts to increase at that time, urban total fare decreases in April.
3. I'd recommend Rural divers to provide trips at Suburban cities as well to increase the Total Fare.
