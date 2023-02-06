# Name
WeatherPy and VacationPy

# Purpose
WeatherPy:- The purpose of the WeatherPy is to visualize the weather of over 500 cities of varying distances from the equator utilizing the citipy Python library, openWeatherMap API and problem-solving skills to create a representative model of weather across cities.

VacationPy:- The purpose is to utilize the weather data skills to plan future vacations using Jupyter notebooks, the geoViews Python library and the Geoapify API and create map visualizations.

# Tools
Python
Jupiter notebooks
Citipy Python library
OpenWeatherMap API
geoViews Python library
Geoapify API

# Instruction
WeatherPy:- Create plots to showcase the relationship between weather varibales and latitude. First use the openWeatherMap API to retrieve data from cities generated in the starter code and then create a series of scatter plots to showcase the following relationships: Latitude vs. Temperature, Latitude vs. Humidity, Latitude vs. Cloudiness, Latitude vs. Wind Speed. Compute linear regression for each relationship, Separate the plots into Northern Hemisphere(greater than or equal to 0 degress latitude) and Southern Hemisphere(less han 0 degress lattitude). Create the following plots: Northern Hemisphere: Temperature vs. Latitude, Southern Hemisphere: Temperature vs. Latitude, Northern Hemisphere: Humidity vs. Latitude, Southern Hemisphere: Humidity vs. Latitude, Northern Hemisphere: Clodiness vs. Latitude, Southern Hemisphere: Cloudiness vs. latitude, Northen Hemisphere: Wind Speed vs. Latitude, Southern Hemisphere: WindSpeed vs. Latitude.

VacationPy: Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example: Amax temperature lower than 27 degress but higher than 21, Wind speed less than 4.5 m/s, Zero cloudiness. Create a new DataFrame called hotel_df to store the city, country, coordinates and humidity. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates. Add the hotel name and the country as additional information in the message for each city on the map.

# Results
Below are some of the results:
![Fig1](https://user-images.githubusercontent.com/115572537/216932202-50967f8a-3178-4f28-97f3-9e2efeb51dc0.png)
![Fig5](https://user-images.githubusercontent.com/115572537/216932474-24881161-40d3-4a7e-bc91-925a2356f9e3.png)
![Fig9](https://user-images.githubusercontent.com/115572537/216932634-1c57c2e2-d1c6-4c62-a69d-b4fbab390d5e.png)
![Fig10](https://user-images.githubusercontent.com/115572537/216932710-214e538d-8065-42f9-9e30-85c325823b74.png)
![Map with points](https://user-images.githubusercontent.com/115572537/216935142-867e33e4-cd2b-495a-b502-7ec197bc809f.png)
![Hover message](https://user-images.githubusercontent.com/115572537/216935203-81f985ba-dfed-4fcc-8346-7bb442266583.png)

# Reference
Jason Lepelmeier,(2023, Feb 01). Class lecture: Power point slides 6.3 Geospacial APIs. Data Analytics and Visualization Bootcamp. University of Minnesota.https://umn.bootcampcontent.com/University-of-Minnesota-Boot-Camp/UofM-VIRT-DATA-PT-12-2022-U-LOLC/-/tree/main/Python%20APIs/6.3
