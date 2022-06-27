# PyBer Ride Sharing Analysis

## Overview

PyBer is a ride-sharing app company looking to improve access to its ride-sharing services and determine affordability for underserved neighborhoods.  Data from January to April 2019 was reviewed to understand the relationships among fares, drivers and rides across urban, suburban and rural cities.

## Resources

- Data Sources: [city_data.csv](Resources/city_data.csv), [ride_data.csv](Resources/ride_data.csv) 
- Software: Python 3.9.12, Jupyter Notebook 6.4.8
- the completed script is available **[here](PyBer_Challenge.ipynb)**

## Findings

This table summarizes data from a total of 120 cities from January to April 2019.

![PyBer_Summary_Chart.png](analysis/PyBer_Summary_Chart.png)

- There is a positive correlation between population density and rides, drivers and total fares.
- There is a negative correlation between population density and average fare per ride and average fare per driver.
- Urban areas have more drivers than riders 

This graph shows total fares collected over the analysis time period for the 3 city types: Rural, Suburban and Urban.

![total_fare_by_city_type](analysis/total_fare_by_city_type.png)

## Summary

- Ridership in rural areas may be lower than urban areas due to lower driver availability or higher cost of fares.  These areas may be the most challenging to build - there is likely lower demand and a perceived high cost per ride may be deterring riders.  The higher average fare per ride is suggestive of longer distance trips.
- Ridership in urban areas is already very high, with a high availability of drivers. Lower average fares per ride and per driver suggest these are shorter distance trips.  If these drivers can be incentivized to service adjacent suburban areas, this tier represents an area with potential for expansion.

### Recommendations

1.  What driver incentives can be implemented to:
    - Increase driver availability in rural areas
    - Shift urban drivers into adjacent suburban areas
2.  What rider incentives can be implemented to:
    - Reduce the average fare per ride in rural areas
3.  Take a closer look at:
    - Can specific cities be identified with very low or high number of drivers?
    - Using the city names, can the data be visualized with average fares and number of drivers per geographic area?  Are there geographic impediments?
    - Are there events which can be identified during this time period which may explain highs and lows?
