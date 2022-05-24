# surfs_up

## Overview
This project reviewed the weather of various locations in Hawaii to help determine the feasibility of opening a shop that sells ice cream and surf boards. Weather data was evaluated from several weather data collection stations in Hawaii to compare possible locations. In this specific analysis, weather patterns in Hawaii in the months of June and December across many years were evaluated. 

## Resources
- Python 3.9.7
- Pandas version 1.3.4
- Flask 1.1.2
- SQLite, sqlalcemy

## Results
The number of weather data points collected in the months of June and December across many years were reasonably similar (1700 data points for June vs. 1517 for December). We can therefore compare the statistical summary data between the two months and infer which month would be better for a surfboard and icecream shop.

### June Weather in Hawaii

![Hawaii Weather Analysis for June](/Resources/June_temps_hawaii.png)

### December Weather in Hawaii

![Hawaii Weather Analysis for December](/Resources/Dec_temps_hawaii.png)

### June Precipitation in Hawaii

![Hawaii Precipitation Analysis for June](/Resources/June_prcp_hawaii.png)

### December Precipitation in Hawaii

![Hawaii Precipitation Analysis for December](/Resources/Dec_prcp_hawaii.png)

## Summary
June is a warmer month overall than December in Hawaii, but not drastically so. June's max temp is 2 degrees hotter and it's also about 4 degrees warmer overall on average. December's minimum temp over the years included in this analysis was a full 8 degrees lower, so it can drop to a colder temperature in December than in June. 

December has more precipitation than June as well. The max precipitation measured in December was 6.42 compared to 4.43 max for June. December's average precipitation was higher as well, at 0.21 vs 0.14 for June. However, according to the quartile breakdown of precipitation data for December, at least a quarter of days have no precipitation, and the dryest 50% of days (bottom two quartiles) are very comparable to June, with 0.03 being the 50% quartile measurement for December and 0.02 being the 50% quartile measurement for June. Therefore at least half of the days of the month of December should be decently low precipitation. 

I would assume based on the warmer and dryer weather in June that the shop will sell more surfboards and ice cream in the summer versus the winter, but it still could make some money in the colder and wetter months. 
