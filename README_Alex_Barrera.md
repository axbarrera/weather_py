# Unit 6 | Assignment - What's the Weather Like?

## Background

This assignment attempts to answer what the weather looks like relative to position to the equator - latitude. Through some visualizations and high-level analysis we'll attempt to answer whether temperature, humidity, cloudiness, and wind speed are correlated with latitude. 

## WeatherPy

In the assignment, we use the OpenWeather API to gather a list of random cities and their coordinates, along with their average humidity, windiness, cloudiness, and temperature. 

Due to the API having inconsistent results, I used a list of cities to gather the relevant data, and then a new list of cities containing the successfully returned API results. 



## Summary / Results

* The temperature vs. latitude graph shows there's a correlation between higher temperatures and shorter distance to the equator. A bell-shaped curve around the 0 point on the Latitude axis shows that temperatures are lowest in general for locations most distant from the equator (0 latitude). There is however a single outlier within the results that shows a lower avg temperature at a distance between 0 and 20 latitude. 

* Humidity vs. Latitude shows a less obvious correlation than our first graph. Without drawing any statistical correlations, it doesn't seem that there's any pattern in this relationship.

* Cloudiness vs. Latitude also shows a lack of pattern in the results, suggesting that cloudiness is unaffected by distance to the equator.

* Windiness vs. Latitude shows that there may be a consistent average windiness across all cities (with few exceptions) that is unaffected by distance from the equator. 

* Further analysis would explore whether air pressure was related to distance from the equator. I'm also interested in exploring the few outliers in the charts that indicate extremes from the patterns displayed. Further analysis would also utilize statistical techniques to determine strength of patterns and non-patterns in the data.

## Copyright

Alex Barrera © 2018. All Rights Reserved.
