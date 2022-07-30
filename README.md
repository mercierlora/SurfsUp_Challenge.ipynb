# SurfsUp_Challenge.ipynb

Overview:
An investor wants to learn more about the weather before committing to build a Surf and Ice Cream shop in Oahu, Hawaii. The investor's main concern is the precipitation forcing the shop to close too frequently. To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database.

Results:
June Statistics for the Temperature and Precipitation
![count](https://user-images.githubusercontent.com/100738861/181937723-04b7b3fc-ef01-4726-ae8a-8870d5326b04.png)

December Statistics for the Temperature and Precipitation
![image](https://user-images.githubusercontent.com/100738861/181937735-839c6d3b-937f-41f7-9648-b3a2e3002585.png)
1) The mean temperature of 75°F for June is higher than the mean temperature of 71°F for December. However, the opposite is true for precipitation. December had the higher precipitation of .22 inches while June had .14 inches.
![image](https://user-images.githubusercontent.com/100738861/181937752-a2af4ff5-4479-4036-9d9f-9c5002c0869e.png)
![image](https://user-images.githubusercontent.com/100738861/181937756-c7b02fbd-45fd-4d1e-96f3-010950521bd8.png)
2)Grouping the data into 15 bins, the histograms visually show how the frequency centers around the two different means. For consistency of the graphs, the ranges of the axes were generated as the same for easier comparison using the minimum and maximum numbers from the descriptive statistics. Using the same range for the temperatures, June appears to have a slight left skew, where December is more symmetrical.
![image](https://user-images.githubusercontent.com/100738861/181937787-6958c734-14e0-47e7-9aa6-3add52d51665.png)
![image](https://user-images.githubusercontent.com/100738861/181937794-058fab05-9a61-4955-964e-0a6ff37f411b.png)
3)As an additional query, the June and December months were filtered from the date. The temperature and precipitation data was then graphed as a scatterplot with a trendline. Reading the slopes of the trendline equations, June (slope = -.037) has a slightly steeper slope than December (slope = -.019), which means as the temperature increases, the precipitation decreases slightly more in June than in December. However, the difference is nominal. Reviewing both scatterplots, the precipitation mostly stays under 3 inches with a few outliers over 3 inches of precipitation.

Summary:
The investor's main concern was getting rained out too frequently. Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably close. The temperature data is not strongly skewed for either month. The ratio of the temperatures to the precipitation for the two months is also reasonably similar with few outliers over 3 inches of precipitation. The data supports opening a Surf and Ice Cream shop year-round.
