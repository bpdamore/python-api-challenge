# python-api-challenge
Working with APIs!


## WeatherPy

In this project I was tasked with finding a randomly selected vacation spot. As with any vacation spot, I need to make sure the weather is perfect! 

I randomly grabbed about 550 Latitudes and Longitudes, found the closest city to them, and then pulled weather information using OpenWeatherMap. 

With that list of cities and weather data, I then used Google's map api to visualize the humidity percentage for all the cities.

In order to find the ideal vacay spot, I pared down the list to some of my ideal conditions. I then used Google's places api to find the nearest hotels because I need a place to sleep.

I added the hotels to the map, and there you have it! I guess I'll buy a plane ticket once this pandemic blows over. 


## Here are some observations

1. There is a definite correlation between lat/long and temperature. I knew that from what I've been told, but it's super cool to see that there is actually a correlation. 

2. There is more Temperature variance in the Northern Hemisphere than in the Southern Hemisphere. While there is a strong correlation in both, the North has more variance. 

3. There isn't much of a correlation in cloudiness, humidity, or wind speed when compared with lat/long. I would have thought there was! 