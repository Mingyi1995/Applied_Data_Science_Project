## Investigation of Urban Outdoor Environment in Citi-BikeUsage

### Abstract 

Citi-Bike is popular in New York City, it is healthy and environmental friendly. Of course, the trip amount between two stations is determined by the location, station in Time Square has much more trip amount than the one located in Jay Street. But we are curious about whether the urban environment have a significant impact on the ridership. Does bike lane attracts more people to ride? Do people prefer to ride under trees during summer time? We collected the ridership data from Jun, 2018 to Sep, counted the trip amount between each pair of stations in Manhattan, calculate the recommend riding route on Google Direction, download street view image through Google Street Statistic, used PSP Net to segment images, and RandomForest classifier to determine the importance of each urban environment related features. And the top three important features are ratios of “van”, “tree” and “building”.

### Main Plots
![](https://i.imgur.com/414iAIXl.jpg)

Fig 1. The trip amount on routes.


![](https://i.imgur.com/dDiGAVGm.jpg)
![](https://i.imgur.com/PL38MwCm.png)

Fig 2. Original street view image and the segamentation result

![](https://i.imgur.com/kFWUXru.png)

Fig 3. The importance of each feature in the model


