# PyBer_Analysis

## Overview:

The purpose of the PyBer analysis was to compare/contrast the ridership data collected from multiple markets. Specifically, the PyBer analysis contains the groupby() function to sort the ridership data by total fare, total riders, total drivers on the index of "type". The three city types include rural, suburban, urban. The final product of creating our PyBer_Summary_Df is attatched below. 



(_PyBer Summary_)<img width="700" alt="PyBer_Summary" src="https://user-images.githubusercontent.com/106042900/177663916-ab272cbb-ba96-4067-a063-d27b5b5d8ca9.png">


## Results: 

To get to the desired end-point the data had to be grouped then ungrouped multiple times to set the proper index. Initially, the orginal merged dataframe was sorted based on type and date with an additional sum function attatched to sum the fare. After the index was reset again, the pivot function was utilized to sort the data based on the date index, the columns as type, and the values as fare. The output of this dataframe shows the fare per city type and the date stamp. This pivot helps us move toward our end-goal of visualizing the multiple line chart. Finally, the fares that were collected per date in the last dataframe were then aggrigated per city type on a weekly basis giving us the final multi-line chart seen below. You will notice that there is a clear distinction in fare totals between the three city types. The line-chart isn't as drastic when we look at the ride date analyzed earlier. The total rides per city were Rural = 125, Suburban = 625, and Urban = 1625. This trend continues into the total drivers per city type as well with Rural = 78, Suburban = 490, and suburban = 2405 total drivers. The total fare per city is Rural = $4327.93, Suburban = $19,356.33, and Urban = $39,854.38. This makes the average fare per ride/fare per driver Rural = $34.62/$55.49, Suburban = $30.97/$39.50, and Urban = $24.52/$16.57. 


<img width="900" alt="Total_Fare_by_City_Type" src="https://user-images.githubusercontent.com/106042900/177666867-f460e342-0c01-42f1-9154-226f0aec12f0.png">

## Summary:

  ### Recommendations: 
1. Evaluate the PNL statement for operating in Rural city types. Overall, Average Fare Per Driver is the highest per city type but it also comes with the highest Average Far per Ride. Also, there aren't many riders in Rural cities so it would be worth looking at keeping the service in that market. 
2. Evaluate customer satisfaction scores from Urban city types then compare their experience with on-time pickup (if possible). The Urban city type is the only category with more Drivers than Riders. You can look to  mobilize the extra Drivers for other delivery projects if there is ever an excess of drivers to Riders. 
3. Touchbase with the Marketing department to research potential holidays around the time-frame of the volume spikes in the line-chart. There is a spike in each city type for late Feb. If the cause is pinpointed you could potentially raise price beforehand to accumulate more earnings. 
