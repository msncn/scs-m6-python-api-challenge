# scs-m6-python-api-challenge

In this challenge we will create a Python script to visualize the weather of over 500 cities of varying distances from the equator.

## WeatherPy
* Create Plots to Showcase the Relationship Between Weather Variables and Latitude
  * Latitude vs. Temperature
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/907e4f2d-745d-40c7-96ea-e5876a859e91)

  * Latitude vs. Humidity
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/81fbe5f8-ef11-49b9-a4c8-2dd3ff5e676e)

  * Latitude vs. Cloudiness
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/0b41c55d-d99e-4c93-815a-9c0f335b25f5)

  * Latitude vs. Wind Speed
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/292887a3-57fe-471d-9b15-6cbe3eed657e)


* Compute Linear Regression for Each Relationship
  * Northern Hemisphere: Temperature vs. Latitude
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/7397d3ad-39bb-401a-839e-b33866a4ae93)

  * Southern Hemisphere: Temperature vs. Latitude
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/a7fcbeed-fc0e-4e78-b0e8-3ef998c2130e)

  * Northern Hemisphere: Humidity vs. Latitude
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/fed2013d-211a-4b2e-8275-148447833f9e)

  * Southern Hemisphere: Humidity vs. Latitude
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/a154e947-7070-45fb-a3ef-4552b3049409)

  * Northern Hemisphere: Cloudiness vs. Latitude
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/edca71e6-2f2c-44cf-b9cd-86260475d46e)

  * Southern Hemisphere: Cloudiness vs. Latitude
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/c8464ad9-2b5e-42f1-b14c-72a9fc45cbbb)

  * Northern Hemisphere: Wind Speed vs. Latitude
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/e03b519d-96b0-4056-866f-d8958c58efac)

  * Southern Hemisphere: Wind Speed vs. Latitude
  ![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/4b640704-279e-4e49-9496-c4af146dc89e)


## VacationPy
1. Create a map that displays a point for every city in the `city_data_df` DataFrame
![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/4fd3fa34-c2b3-4df2-9233-f6fed44b21fc)

2. Narrow down the city_data_df DataFrame to find your ideal weather condition
3. Create a new DataFrame called `hotel_df` to store the city, country, coordinates, and humidity
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates
![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/c281ec6e-8a5c-452e-b971-89dd2c795538)

5. Add the hotel name and the country as additional information in the hover message
![image](https://github.com/msncn/scs-m6-python-api-challenge/assets/130943141/24c02a6c-f176-4f97-9945-5b5c8b87f4ae)
