# Server-Side APIs: Weather Dashboard

Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. In this work segment, I have built a weather dashboard using the OpenWeather API.


## Instructions

Built a weather dashboard application with search functionality to find current weather conditions and the future weather outlook for multiple cities in view of traveler.

```
As a traveler
I want to see the weather outlook for multiple cities
so that I can plan a trip accordingly
```

Here under some guidelines how I have developed the application:

* Used the [OpenWeather API](https://openweathermap.org/api) to retrieve weather data for cities. 

* Used AJAX to hook into the API to retrieve data in JSON format.

* My app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

* It displays the following under current weather conditions:

  * City

  * Date

  * Icon image (visual representation of weather conditions)

  * Temperature

  * Humidity

  * Wind speed

  * UV index

* I have included a search history so that users can access their past search terms. Clicking on the city name should perform a new search that returns current and future conditions for that city. 

* Included a 5-Day Forecast below the current weather conditions. Each day for the 5-Day Forecast displays the following:

  * Date

  * Icon image (visual representation of weather conditions)

  * Temperature

  * Humidity

![weather dashboard](./Assets/Server-Side-API.png)


