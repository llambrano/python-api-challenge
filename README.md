# python-api-challenge
###### by Libardo Lambrano

## Background <a name="top"></a>

Using Python requests, APIs, and JSON traversals prove that weather temperatures are higher as cities get closer to the equator [(WeatherPy)](#weartherpy). Identify world's cities with perfect weather for an ideal vacation, and find the closet hotel to the city center using Google Places API [(VacationPy)](#vacationpy). 

## WeatherPy <a name="weatherpy"></a>
![](images/equatorsign.png)

**Request**

>Utilize the OpenWeatherMap API to create a representative model of weather across world cities.

**Tasks**

create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot add a sentence or two explaining what the code is and analyzing.

Run linear the regression on each relationship, separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). Create a series of scatter plots to showcase the following relationships:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

[Solution](WeatherPy/WeatherPy.ipynb)

## VacationPy <a name="vacationpy"></a>
![](images/vacationpy.png)

**Request**

> Utilize the OpenWeatherMap API to create a representative model of weather across world cities.

**Tasks**

* Indentify cities with ideal weather conditions. 
* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

[Solution](VacationPy/VacationPy.ipynb)








