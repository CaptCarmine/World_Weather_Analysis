# World_Weather_Analysis

## Overview

Assignment Overview is to refactor code from the assignment to create a marker map of locations to visit.

## Steps

We will do this in aa number of steps:

1. One I will create a random assortment of Latitude and longitude's using the the random module in python.
2. We will use the citiPy module to find a number of cities associated with the list of random latitudes and longitudes.
3. Use the openweather API to find the weather of each city found.
4. Use the google API to create a figure showing what the world of all cities from our random assortment of locations, see below figure for what the output looks like
![Vacation Search](https://github.com/CaptCarmine/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png?raw=true)
5. Prune the list of over 600 cities to 4.
6. take the 4 cities we decided on, and create a map using the gmaps.directions_layer command.
![Travel Map](https://github.com/CaptCarmine/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png?raw=true)
7. Do a final map showing the weather of the 4 cities we decided on visiting in our previous model.
![Travel Map Weather](https://github.com/CaptCarmine/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png?raw=true)
