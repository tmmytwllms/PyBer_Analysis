# PyBer_Analysis

## Resources:
- Data:
  -city_data.csv
  -ride_data.csv
- Software:
  -Python 3.7.8
  -Jupyter Notebook
  -Pandas
  -Matplotlib
  -Microsoft Excel 2019

## Overview
This analysis looked at two sets of data from PyBer, a ride sharing company. The goal of the analysis for the PyBer ride data was to create a data frame with new summary statistics, and a chart showing total weekly fare totals by city type. The two csv files were again merged into the PyBer dataframe, which was then used to calculate the previously mentioned statistics for this data set to assist in providing recommendations for PyBer.

## Results
### PyBer Statistics by City Type
Our first task was to create a set of summary statistics for each city type. These statistics included total rides, total drivers, total fares, average fare per ride, and average fare per driver. Once these new results were calculated, they were used to create a data frame to display them.
In analyzing this new data frame, we saw that urban cities had the largest amount of total fares, total drivers, and total rides. Additionally, urban cities had the lowest average fare per ride and per driver. Moving from urban cities to suburban and then rural, we see a decrease in total rides, total drivers, and total fares, but an increase in average fare per ride and per driver. 
![pyber_summary_df](https://user-images.githubusercontent.com/82389466/119290893-72237f80-bc1b-11eb-9abf-e96f82f793da.png)
### Weekly PyBer Fares by City Type
Our second task was to determine the weekly amount of total fares for each city type, and display this within a line graph. This data was calculated using a newly created data frame to group fares by city type and date, and then using the resample function, we determined each city type's weekly fares from January 1st, 2019, to April 28th, 2019.
In analyzing the Total Fare by City Type line graph for urban, suburban, and rural cities, we see that weekly fares for urban cities mostly fall within $2000-$2500, with the first week in January dipping below to roughly $1700. Urban fares stay fairly inconsisten for the time frame, and saw the most week-to-week variability in March.
For suburban cities, we see that weekly fares were somewhat consistent , with the lowest total fares around $750 in the first week of January, then fluctuating between the $500-$1500 mark for the time frame. We see another dip to roughly $750 in the second week of April and a spike to roughly $1450 in late February.
For rural cities, we see inconsistent weekly total fares for the time period. Only 2 weeks, the last two weeks of March, saw continued increase. Week-over-week, we see a trend of an increase in fares and then a decrease, which repeats itself. Fares for rural cities were the lowest, falling between the $0-$500 mark, with the last week of march seeing a total of roughly $500 in fares.
![PyBer_fare_summary](https://user-images.githubusercontent.com/82389466/119292174-dba48d80-bc1d-11eb-82a0-6bbe6dc731eb.png)
## Summary
Based on the data that was analyzed, several recommendations could be made for each city type and time frame.
My recommendations based on each city type are:
-Urban
  1. Reducing either the fare price or total drivers during the month of January to either increase the amount of rides or cut costs, respectively.
-Suburban
  1. Increase the number of drivers in this city type, so fare prices can be reduced, which may allow for more rides.
  2. Increase the number of drivers in late February and late April to capture more rides.
-Rural
  1. Increase the number of drivers in rural areas so fare prices can be reduced. Average fares per ride are 1.4 times higher than urban rides, and average fares per driver are      3.3 times higher than urban drivers
  2. Increase the number of drivers towards the end of each month, as the end of each month saw mostly hire fares.
