# Surf's Up

## Purpose
1. Explain the structures, interactions, and types of data of a provided dataset.
2. Differentiate between SQLite and PostgreSQL databases.
3. Use SQLAlchemy to connect to and query a SQLite database.
4. Use statistics like minimum, maximum, and average to analyze data.
5. Design a Flask application using data.

## Overview:
A potential investor having a negative previous investment experience due to weather and attracting tourist in Hawaii wants to learn more about the weather trends on the Oahu island before committing to build a Surf and Ice Cream shop.  The investor's main concern is the precipitation forcing the shop to close too frequently.  To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database. 

## Results:
### June Statistics for the Temperature and Precipitation

      ![Pic_1]
      
### December Statistics for the Temperature and Precipitation

      ![Pic_2](https://github.com/Baylex/surfs_up/blob/main/Resources/dec_stat_temp_prcp.PNG)

1. The mean temperature of 75°F for June is higher than the mean temperature of 71°F for December.  However, the opposite is true for precipitation.  December had the higher precipitation of .22 inches while June had .14 inches. 

![Pic 3](https://github.com/Baylex/surfs_up/blob/main/Resources/june_temp_graph.PNG)
![Pic 4](https://github.com/Baylex/surfs_up/blob/main/Resources/dec_temp_graph.PNG)

2. Grouping the data into 15 bins, the histograms visually show how the frequency centers around the two different means.  For consistency of the graphs, the ranges of the axes were generated as the same for easier comparison using the minimum and maximum numbers from the descriptive statistics.  Using the same range for the temperatures, June appears to have a slight left skew, where December is more symmetrical.    

![Pic 5](https://github.com/Baylex/surfs_up/blob/main/Resources/june_temp_prcp_graph.PNG)
![Pic 6](https://github.com/Baylex/surfs_up/blob/main/Resources/dec_temp_prcp_graph.PNG)

3. As an additional query, the June and December months were filtered from the date.  The temperature and precipitation data was then graphed as a scatterplot with a trendline.  Reading the slopes of the trendline equations, June (slope = -.037) has a slightly steeper slope than December (slope = -.019), which means as the temperature increases, the precipitation decreases slightly more in June than in December.  However, the difference is nominal.  Reviewing both scatterplots, the precipitation mostly stays under 3 inches with a few outliers over 3 inches of precipitation. 

## Summary:
The investor's main concern was getting rained out too frequently.  Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably close.  The temperature data is not strongly skewed for either month.  The ratio of the temperatures to the precipitation for the two months is also reasonably similar with few outliers over 3 inches of precipitation.  The data supports opening a Surf and Ice Cream shop year-round.
