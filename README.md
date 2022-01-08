# Surf's Up

## Purpose
* Explain the structures, interactions, and types of data of a provided dataset.
* Differentiate between SQLite and PostgreSQL databases.
* Use SQLAlchemy to connect to and query a SQLite database.
* Use statistics like minimum, maximum, and average to analyze data.
* Design a Flask application using data.

## Overview:
A potential investor having a negative previous investment experience due to weather and attracting tourist in Hawaii wants to learn more about the weather trends on the Oahu island before committing to build a Surf and Ice Cream shop.  The investor's main concern is the precipitation forcing the shop to close too frequently.  To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database. 

## Results:
### June Statistics for the Temperature and Precipitation

![Pic_1](https://github.com/krmcclelland/surfs_up/blob/main/June_Temp_Stats.png)
      
### December Statistics for the Temperature and Precipitation

![Pic_2](https://github.com/krmcclelland/surfs_up/blob/main/December_Temp_Stats.png)

1. The mean June temperature of 75°F is higher than the mean December temperature of 71°F.  However, the opposite is true for precipitation, whereas December precipitation of .22 inches while June had .14 inches. 

![Pic 3](https://github.com/krmcclelland/surfs_up/blob/main/June_Temp_Observations.PNG)
![Pic 4](https://github.com/krmcclelland/surfs_up/blob/main/December_Temp_Observations.PNG)

2. Grouping the data, the histograms shows the frequency centers around the two different means.  For consistency of the graphs, the ranges of the axes were generated as the same for easier comparison using the minimum and maximum numbers from the descriptive statistics.  Using the same range for the temperatures, June appears to have a slight left skew, where December is more symmetrical.    

![Pic 5](https://github.com/krmcclelland/surfs_up/blob/main/June_prcp.png)
![Pic 6](https://github.com/krmcclelland/surfs_up/blob/main/December_prcp.PNG)

## Summary:
The investor's main concern was being rained out, and revenue loss.  Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably close.  The temperature data is not strongly skewed for either month.  The ratio of the temperatures to the precipitation for the two months is also reasonably similar with few outliers over 3 inches of precipitation.  The data supports opening a Surf and Ice Cream shop year-round.
