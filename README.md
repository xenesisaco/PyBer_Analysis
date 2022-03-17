# PyBer_Analysis
# Overview of the Analysis

The CEO of a rideshare company would like to compare the following data from 3 demographic cities (Rural, Suburban & Urban): 
- Total Rides
- Total Drivers
- Total Fares
- Average Fare per Ride
- Average Far per Driver

By analyzing each city's data listed above, recommendations to the CEO can be made: Which city if the lowest performing, do employed drivers make a difference in fares made, does a more populated region (with more demand) generate more money, and how much more?

## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
### Summary DataFrame

Starting with the total amount of rides, it seems as the more populated an area is, the more total rides that occur. This trend is also seen throughout all of the different columns/series in this summary. However, when the average fare price and the average fare per driver is taken into account, the amount charged is higher when there are less drivers and less total rides. This is also the case with the average fare per driver. 

There is more demand and activity from the more populated, Urban demographic (total rides being 125 / total drivers: 78), than the Rural City type (total rides being 1625 / total drivers: 2405). Suburban is in the middle of the two, but leaning more towards the lower portion of the spectrum (total rides being 125 / total drivers: 78).

![image](https://user-images.githubusercontent.com/98041751/158902158-e9f5ab5f-7f19-48c2-9038-22387b3a670f.png)

When looking at the Total Fare by City Type, one can see that the fare from rural (less populated) gains the least amount of fares compared to Urban (most populated).

Although in the Urban City Type the Average fare per Ride and the Average Fare per Driver is the lowest, the overall total fares in Urban Cities ($39,854.38) is more than 9 times the amount of rural areas ($4,327.93) and twice as much than Suburban areas ($19,356.33)

![image](https://user-images.githubusercontent.com/98041751/158902208-7c7c08d8-638a-42b5-a9c3-6d5907556ddc.png)

## Summary

From the data, it seems as with less drivers and total ride activity, the average fare is higher and the average fare per diver is significantly, which could lead to overall less demand. With Urban demand being the highest, it also generates the most revenue, beating suburban fares by twice as much and Rural areas by 9 times!

There may be more potential in Suburban areas, however. Notice that the number of drivers is almost 3 times less than Urban areas, and yet, it meets the Urban areas fare totals by more than half. If the CEO were to focus efforts there, there could be potential to beat Urban areas int terms of total fares and less drivers!
