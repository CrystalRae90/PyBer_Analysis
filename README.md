# PyBer_Analysis

## Overview of the Analyis

The purpose of this analysis was to review ride data across different cities to determine any trends related to type of city. 

## Results

### Data

In order to analyze the data, we needed to merge the city data and ride data. Using a merged data frame we were able to gather some basic data: 

- Total Rides
- Total Drivers 
- Total Fares ($)
- Average Fare Per Ride
- Average Fare Per Driver 

All data was split based on the city type: Rural, Urban, or Surburban. 

### Analysis

Once the data was compiled, we were able to summarize it as shown below: 

!["Pyber_Summary.png"]("Analysis/Pyber_Summary.png")

Looking at the data, we can quickly see there is significantly more rides in urban areas than rural, which also corresponds to the total driver count. Conversely, rural rides are on average more expensive than those in urban areas. For both cases, suburban rides and driver count remain the middle as well as for average fare costs. 

One observation is that the average fare per driver is higher than the average fare per ride for both suburban and rural areas. This coincides with the fact that there are less drivers that total rides for those two city types but not for urban areas. 

When we look at the total fare grouped by week for each city type, we see the below graph. 

!["Pyber_Fare_Summary.png"]("Analysis/Pyber_Fare_Summary.png")

The chart shows us that there are similar trends for total fares across each type, but it does highlight that urban areas generate the most total fares. 

## Summary 

While it is very apparent that urban areas generate more total fare revenue than the other two, it would appear that the average fare per driver is significantly lower. Using that, there are 3 potential items that Pyber can look at: 

- Increase market share of ride business to allow for more rides per driver for urban areas 

Assuming that they are not the only ride business in the areas, increasing the number of total rides but not fluxuating the driver count would help with total fares but allow drivers to earn more per driver. This would undoubtedly help with retention 

- Examine Mileage and Determine other factors 

While we have been assuming that suburban and rural areas have an increase mileage factor, it would be good to analyze the data set to see how mileage or other factors are impacting the total fare cost and the the average fare per driver. 

- Map data for entire year

In the line graph, we primarily looked at the January to April data. It would be interesting to see if there was any changes to the data set when you look at a full year or longer than that. 

Overall, there are most likely other factors influencing the data and we would need to continue to expand our analysis to make meaningful suggestions. 

