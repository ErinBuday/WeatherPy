Python API
=============================================================================================
What's the Weather Like?

Whether financial, political, or social—data's true power rests in its ability to answer questions definitively. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

WeatherPy
=========
Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using CityPy, a simple Python library, and the OpenWeatherMap API.  The visualizations includce a series of scatter plots to showcase the following relationships:

  * Temperature (F) vs. Latitude
  * Humidity (%) vs. Latitude
  * Cloudiness (%) vs. Latitude 
  * Wind Speed (mph) vs. Latitude

The WeatherPY Script
====================

  * Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.
  * Performs a weather check on each of the cities using a series of successive API calls.
  * Includes a print log of each city as it's being processed with the city number and city name.
  * Saves both a CSV of all data retrieved and png images for each scatter plot.

Observable Trends
=================
1. Southern Hemisphere climates tend to be slightly milder than those at similar latitudes in the Northern Hemisphere. This is because the Southern Hemisphere has significantly more ocean and much less land; water heats up and cools down more slowly than land.
2. Highest temperature is found at 0 latitude and as the latidude increases or decreases, temperature drops. This happens as equatorial region receives sunlight straight with less or no angle due to curvature shape of earth.
3. Latitude doesn't have a strong iinfluence on wind speed. The speed of the wind is controlled by the strength of the air pressure gradient, the stronger the pressure gradient the higher the wind speed.
