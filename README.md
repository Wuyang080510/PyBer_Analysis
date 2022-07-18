# PyBer_Analysis
Analyze rideshare data and create compelling visualizations for PyBer with Pandas and Matplotlib.

## Overview
In this challenge, I implemented data analysis for PyBer, a python based ride-sharing app company. I performed an exploratory analysis of the ride-sharing data, merged DataFrames, and generated graphs and charts to showcase the relationship between the type of city, the number of drivers, ride counts, and fare amount. The analysis will help PyBer better understand its gap in ride-sharing services and determine the affordability for underserved neighborhoods. 
### Purpose
- Proficiently use groupby() function to group ride-sharing data by city types. 
- Calculate the number of drivers and rides, total amount of fares, average fare amount per ride, and average fare amount per driver by city types with python functions.
- Generate summary DataFrame with Pandas.
- Create a pivot table with the pivot() function
- Create a sum of fare by week DataFrame with resample() function
- Visualize ride-sharing data with matplotlib

## Results
### Deliverable 1: Ride-Sharing Data Summary by City Types
PyBer's rideshare service is available in 120 cities. These cities fell into three types: urban cities, suburban cities, and rural cities. Urban cities had the highest number of rides in 2019, more than twice as many rides as the combined number of rides of rural cities and suburban cities. Urban cities also had the highest number of drivers and total fares amount. Rural city drivers earned more on each ride than urban and suburban cities.   
![Ride-sharing Data Summary Table by City Type](https://github.com/Wuyang080510/PyBer_Analysis/blob/main/Table_Images/Summary%20Table%20by%20City%20Type.png)

From the bubble chart, we can find out that data points are clustered into three groups. Urban cities had more rides and more drivers. But with a large number of drivers available, the competition is higher in urban than in suburban and rural areas. This led to a more affordable rate for customers living in urban cities. In contrast, there were fewer cities in rural areas that had ride-sharing services. The total number of ride per city in rural areas were mostly less than 10 in 2019. As there were fewer ride-sharing drivers, people in rural cities were willing to pay higher prices for the service. Suburban cities, clustered in the middle of the scatter plot, had a medium number of rides with a competitive fare rate.  
![PyBer Ride-Sharing Data 2019](https://github.com/Wuyang080510/PyBer_Analysis/blob/main/Table_Images/Fig1.png)

Note: Circle size correlates with driver count per city

### Deliverable 2: Weekly Fare Amount for Each City Type
Same as shown in the summary table, urban cities had higher weekly total fare amounts than the other two city types. Rural cities had lower weekly total fare amounts from January to April in 2019. 
The weekly total fare amount from January to April was stable across the three city types. The total fare amount for all the three city types increased in the second half of February. The weeks at the beginning of January and the end of April were slower weeks for ride-sharing services. 

![Weekly Total Fare by City Type](https://github.com/Wuyang080510/PyBer_Analysis/blob/main/Analysis/PyBer_Fare_Summary.png)

## Summary
In the urban cities, there were 1.48 drivers for each ride. 
The ratio of the driver to ride for suburban cities was 0.78 drivers for each ride. 
The ratio of the driver to ride for rural cities was 0.624 drivers per ride. 
Judging by the numbers above, there was an oversupply of drivers in urban cities. Suburban and rural neighborhoods had high requests for ride-sharing services, but the drivers were not enough to meet customers' needs. 

- PyBer CEO should consider implementing campaigns to recruit more drivers for suburban cities and rural cities
- PyBer could better pair urban city drivers with customers with a precise location matching function in the app to reduce the competition among drivers over a single ride. 
- Campaigns could be planned and implemented in January to encourage ride-sharing. 

 
