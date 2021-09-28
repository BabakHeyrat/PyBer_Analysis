# PyBer Breakdown

## Overview of Project

*  The purpose of this project was to first create a DataFrame that summarized PyBer's ride-sharing data by city type in a neat table displaying total number of rides, drivers, and fares. We then further wanted to break down the data into a chart that illustrated weekly trends in PyBer activity by city type. 

## Analysis

### PyBer Summary by City Type
![PyBer_Summary.png](/resources/PyBer_Summary.png)
		
* After having merged both the city and ridership data into a single dataframe, I condensed the data to display the city type: rural, suburban, and urban cities are our main regions of interest. We can see that outside large urban areas, the total number of PyBer drivers, rides, and fares steadily decreases. Inversely, the more urbanized the city, with an increasing number of drivers and rides, the average fare per ride and average far per driver decreases. This illustrates the more urbanized a city, the larger the population, the larger the total number of drivers and rides; allowing the average fare per ride and average fare per driver to decrease. 


### Weekly PyBer Activty
![PyBer_Fare_Summary.png](analysis/PyBer_Fare_Summary.png)
* We then wanted to look at weekly changes in total fares($USD) per city type for the first four months of 2019. Here we can see there was a noticeable increase in total amount of fares towards the last week of February across all three types of cities. All three city types also exhibit a significant drop in total fares during the middle of April 2019. 
		

## Recommendations
Based on the findings above, I have three recommendations in eliminating the discrepancies found across the three types of cities. 

1. **Lower Suburban and Rural Prices**: One way we can normalize prices is by lowering the fares charged per ride and driver in suburban and rural areas to better track with the averages found in urban areas.
2. **Increase Urban and Suburban Prices**: Conversely, we can increase the average fare in urban and suburban areas to match the higher average fare price found in rural areas. 
3. **Change Prices During Sudden Fluctuations in PyBer Activity**: During sudden upturns in PyBer activity that are found throughout the year, we can charge more in the relatively more inexpensive urbanized areas and less in the more expensive rural and suburban areas; leading to more homogenized average fares per ride and per driver per city type. We can do the inverse during sudden downturns in PyBer activity. 

