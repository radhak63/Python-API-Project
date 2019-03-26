# Python-API-Project

This program was written by Radha Mahalingam (3-25-19)

Python API project

This project amplifies the data's true power - i.e its ability to answer questions definitively. 
By using Python requests, APIs, and JSON traversals, this program answers definitively a fundamental question: "What's the weather like as we approach the equator?"

While we all know that "It gets hotter as we approach the equator", this data analysis proves it beyond any doubt

# WeatherPy

In this example,  a Python script is created to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a simple Python library - (https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

A series of scatter plots are created using the data obtained through APIs to showcase the following relationships:

   Temperature (F) vs. Latitude
   Humidity (%) vs. Latitude
   Cloudiness (%) vs. Latitude
   Wind Speed (mph) vs. Latitude

This Jupyter notebook accomplishes the following :

  Randomly selected **at least** 500 unique (non-repeat) cities based on latitude and longitude.
  Performed a weather check on each of the cities using a series of successive API calls.
  Included a print log of each city as it's being processed with the city number and city name.
  Saved both a CSV of all data retrieved and png images for each scatter plot.

Based on the scatter plots, the following three prominent trends are clearly observed. 

    As expected, the weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude). 

    # There is no strong relationship between latitude and cloudiness. However, it is interesting to see that a strong band of cities sits at 0, 80, and 100% cloudiness.

    # There is no strong relationship between latitude and wind speed. However, in northern hemispheres there is a set of cities with over 20 mph of wind.