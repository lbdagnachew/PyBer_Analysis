# PyBer_Analysis

## Overview 
The purpose of this project is to analyze and visualize PyBer 2019 ride-sharing data using Python, Pandas and Matplotlib, to help the company improve access to ride-sharing services and determine affordability for underserved communities.

### Resources: 
Software: Python 3.9.7, Anaconda 4.10.3, Jupyter Notebook 6.4.5 
Data Source: city_data.csv, ride_data.csv

#### Results: 

Total Weekly Fares by Cirty Type:

![Total_Fare_by_City_Type](https://user-images.githubusercontent.com/101952961/184518659-486be4f8-eb1a-4e6d-bcd6-6c353012a097.PNG)

The graph above shows the weekly fares of each city types from January 1, 2019 through April 29, 2019. Fares in Urban cities hovered between $1,500 - $2,500, with resistance at $2,500. Suburban city fares were between $500 - $1,500. Lastly, Rural city fares remained between $0 - $500.

![Results](https://user-images.githubusercontent.com/101952961/184518633-f10d712b-ee21-49b6-a681-86ec8b399004.PNG)

There are only three categories of city types in this analysis: Urban, Suburban, and Rural:
1. Rural cities has the least amount of drivers (78), rides (125) and total fares ($34.62)
2. Suburban cities have 2nd most drivers (625), rides (490) and total fares ($39,50).
3. Urban cities have the most amount of drivers(1,625), rides (2,405) and lowest total fares ($16.57). 

#### Summary: 
The majority of PyBer's customers and drivers are in Urban cities. However, due to the excess supply of drivers in Urban cities, the average fare per driver is only $16.57, which is the lowest of any market. There is a good balance of drivers and rides, which maintains a high average fare per driver. In all metrics analyzed, Suburban cities are consistently ranked in second place. Rural cities on average have the fewest number of drivers and rides. Due to the low supply of drivers, average fare prices in Rural areas are the highest of any city type at $34.62 per ride.

##### Recommendation: 

More drivers are needed to service Rural cities to lower fare prices in these areas.


