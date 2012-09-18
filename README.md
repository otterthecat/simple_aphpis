simple_aphpis
=============

a collection of php clases to connect to some web apis

* YahooWeatherAPI.php

- requires curl.
- details on getting a WOEID can be found here at http://developer.yahoo.com/weather/index.html.
- currently, getWeather() method returns an array with 2 keys - **conditions** and **forecast**.

* YahooWeatherAPI upcoming changes (when I get around to it):

- add ability to get woeid withing the annoying goose chase
- add a slew of getter methods for more surgical data returns