# python-api-challenge

WeatherPy

Python script visualizes the weather of 500+ cities across the world of varying distance from the equator. OpenWeatherMap API is utilized here to create a representative model of weather across world cities.

The following relationships are shown through scatter plots:
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Linear regression is then run on each relationship, separating findings into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude


VacationPy

Jupyter-gmaps and the Google Places API is used to plan future vacations.

Data is analyzed to find locations based on ideal weather conditions:

- Wind speed less than 10 mph
- Zero cloudiness

Hotels are plotted on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.