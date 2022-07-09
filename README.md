# PyBer_Analysis

## Overview
Using Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type and with MatPlotLib create multiple-line graph that shows the total weekly fares for each city type. 

## Purpose
Analyze the given datasets, ride_data("location", "date" and "fare" for each ride) and city_data ("city","drivers","city type") and find out how the data differs by "city type" and how those differences can be used by decision-makers at PyBer.

## Resources
  - Jupyter Notebook
  - Python 3.7.6
  - Dependencies
      - Python Pandas library
      - Python Numpy library
      - Python MatPlotLib library

## Requiements

1. Create a summary DataFrame of the ride-sharing data by city type. 
2. Using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type.
3. Report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results


As per the analysis,
- It shows that Urban cities have higher numbers of rides, but the average fare per ride is less than in rural cities. ($24.53 vs $34.62)
- In urban cities, the total fares are higher than in rural and suburban cities. ($39,854.38 vs $4,327.93) ,($39,854.38 vs 19,356.33)
- In urban cities the average fare per driver is less than in rural cities. ($16.57 vs $55.49)

![PyBer_Analysis](https://github.com/Lauramasonjar/PyBer_Analysis/blob/main/PyBer%20Summary%20DataFrame.png)

In the multiple line chart,
 - We can get information on the weekly basis of "Total Fare by city type" within the given timeframe of January 2019 to April 2019.
 - The chart shows the ride-sharing company has more total fares and profits in urban cities than in suburban and rural cities.
 - In the chart below it shows urban cities has reached its total fare of $2500 in the month of February, but rural cities maximum total fare only reached $500, also in the month of February. 
 
![PyBer_Analysis](https://github.com/Lauramasonjar/PyBer_Analysis/blob/main/Total%20Fare%20By%20City%20Types.png)

## Summary

- The urban city rides make more revenue than the rural city rides, but rural city rides are more profitable than the urban area.
- It would be a good idea to focus on improving the plan to make urban city rides more profitable.
- It would also be a good idea to focus on the drivers count, although urban cities have less rides than the drivers count. 
- The CEO should consider increasing the per mile charges in urban cities because there are more short trips and the average fare per driver is less.
- The CEO should also consider increasing the drivers count, they can charge more for drivers who are consistent in their work. 
