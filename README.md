# PyBer_Analysis

## Overview of the analysis
As a data analyst in PyBer, a Python-based ride-sharing app company. The main tasks include performing exploratory analysis on data in some very large CSV files, creating visualizations to tell a compelling story about the data, and writing Python scripts using Panda's libraries, the Jupyter notebook, and Matplotlib to create charts that showcase relationships. 

For this particular assignment. Pandas library was used to create a summary DataFrame of the ride-sharing data by city type. Then Matplotlib and Pandas were used to create a multiple-line graph that shows the total weekly fares for each city type. 

## Results

### DataFrame by city type

- Rural city type has the least amount of drivers, rides, and total fares.
- Urban city type has the most amount of drivers, rides, and total fares.
- Rural city type has the highest average fare per ride and the highest average fare per driver.
- Urban city type has the lowest average fare per ride and the lowest average fare per driver. 
- Suburban city type is in the middle with total rides, total drivers, total fares, average fare per ride, and average fare per driver. 

![DataFrame_City_Type](https://user-images.githubusercontent.com/84931545/126914309-8942523e-6f42-402e-a722-cf429d08c655.PNG)


### Multiple-line graph for each city type

Urban city type observed to have the highest total fare even on a weekly basis, while rural city type has the lowest total fare by week. Besides a drop in fare from all city types in the last week of February, there are no similar fluctuations among the 3 city types. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/84931545/126914313-f6193033-d368-4de4-89de-66f9b7c6ade7.png)


## Summary

### Recommendations to CEO

1. Rural area needs a higher fare due to the low number of drivers and riders.
2. Increase fare in particular weeks during which total fare was observed to be dropping in the corresponding city type in order to maximize profit.
3. Adding a base fee per ride in the Urban or Suburban cities since the trips are more likely to be short and drivers are not earning much per trip. 
