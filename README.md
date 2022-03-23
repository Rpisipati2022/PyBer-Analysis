# PyBer-Analysis
Analyzing and visualizing ridesharing data with Python

## Overview:
The purpose of this project is to analyze ride share data from the Jan – mid-May, 2019 timeframe to get an understanding of how PyBer services are used by people living in different locales. These locales are segregated into urban, suburban and rural. With varying population density it will be helpful to examine current usage of PyBer services: - conclusions regarding accessibility and affordability, so that better offerings may be tailored in the future. Another objective of this analysis is to gain experience in data visualization: how can the various results obtained best be visualized?

## Results:
Results of the analysis are shown in the table below.
<img width="684" alt="Ridership Analysis" src="https://user-images.githubusercontent.com/99691015/159809507-a35a2bbc-4b87-4dbf-8050-37e6001e4e1b.png">

### Key findings include:
- There are significantly more rides used in urban areas than in suburban (1625 to 625) or rural areas (1625 to 1225). This is a result of urban cities having 5x more drivers than suburban areas and almost 30x more drivers than in rural areas.
- Rural areas are currently the least served locales with the fewest number of rides, served by the fewest number of drivers.
- However, this paucity of rural drivers results in rural areas having the highest fares/driver of the three area: $55.49 for rural vs $39.50 for suburban and $16.57 for urban areas. 
- There is a strong relationship between overall revenue and ratio of drivers to rides: drivers/rides = 1.5 (urban), 0.8 (suburban) and 0.6 (rural).

## Summary:
Based on the analysis the following business recommendations can be made:

1. Incentivizing more drivers to serve rural areas will increase revenue in the highest revenue/ride area. However, a deeper analysis of this demographic will have to be conducted to understand the underlying data: 
        o	are there fewer rides due to fewer drivers?
        o	Does the average trip cover longer distances taking more time thereby resulting in fewer free drivers during peak times?
o	Is there in general lower demand for ride share services in rural areas where people live far apart and are more self-reliant or on neighbors?
2. Experiment with lower fares in rural areas to encourage ridership. Do this after examining the results from recommendation a) above.
3. Increase fares in urban areas: currently this is less than half that of suburban rides and only a quarter of the average rural ride. While this may be difficult in the short term, utilizing peak pricing surcharges would help close this gap.
