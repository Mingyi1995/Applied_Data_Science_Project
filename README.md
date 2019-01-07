## Perceived Safety Score and Violence

### Abstract 

Citi-Bike is popular in New York City, it is healthy and environmental friendly. Of course, the trip amount between two stations is determined by the location, station in Time Square has much more trip amount than the one located in Jay Street. But we are curious about whether the urban environment have a significant impact on the ridership. Does bike lane attracts more people to ride? Do people prefer to ride under trees during summer time? We collected the ridership data from Jun, 2018 to Sep, counted the trip amount between each pair of stations in Manhattan, calculate the recommend riding route on Google Direction, download street view image through Google Street Statistic, used PSP Net to segment images, and RandomForest classifier to determine the importance of each urban environment related features. And the top three important features are ratios of “van”, “tree” and “building”.

### Main Plots
<center class="half">
    <img src="https://i.imgur.com/414iAIXl.jpg">
</center>
Fig 1. The trip amount on routes.

<center></center> class="half">
    <img src="https://i.imgur.com/dDiGAVGm.jpg"><img src="https://i.imgur.com/PL38MwCm.png">
</center>

Fig 2. Original street view image and the segamentation result

<center class="half">
    <img src="https://i.imgur.com/kFWUXrum.png">
</center>
Fig 3. The importance of each feature in the model


