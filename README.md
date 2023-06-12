# scs-m6-python-api-challenge

In this challenge we will create a Python script to visualize the weather of over 500 cities of varying distances from the equator.

## WeatherPy
* Create Plots to Showcase the Relationship Between Weather Variables and Latitude
  * Latitude vs. Temperature
  * Latitude vs. Humidity
  * Latitude vs. Cloudiness
  * Latitude vs. Wind Speed

* Compute Linear Regression for Each Relationship
  * Northern Hemisphere: Temperature vs. Latitude
  * Southern Hemisphere: Temperature vs. Latitude
  * Northern Hemisphere: Humidity vs. Latitude
  * Southern Hemisphere: Humidity vs. Latitude
  * Northern Hemisphere: Cloudiness vs. Latitude
  * Southern Hemisphere: Cloudiness vs. Latitude
  * Northern Hemisphere: Wind Speed vs. Latitude
  * Southern Hemisphere: Wind Speed vs. Latitude

## VacationPy
1. Create a map that displays a point for every city in the `city_data_df` DataFrame
2. Narrow down the city_data_df DataFrame to find your ideal weather condition
3. Create a new DataFrame called `hotel_df` to store the city, country, coordinates, and humidity
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates
5. Add the hotel name and the country as additional information in the hover message
