# python-api-challenge  

## WeatherPy
* Based on 1500 ramdon coordinates generated by numpy within latitude ranges of -90 to 90, and longitude ranges of -180 to 180, a sample size 620 unique nearest cities was generated.  
* Using OpenWeatherMap API, current weather data pertaining to the sampled cities was retrieved and stored into a city data dataframe and csv file.  
* Scatter plots and linear regressions were created to illustrate the relatinoships between 'latitude vs max temp', 'latitude vs humidity', 'latitude vs cloudiness', and 'latitude vs wind speed'.  
* Besides max temperature and latitude, all other plotted relatinoships are insignificant.  

## VacationPy  
* Created a map plot of all the cities within the city data dataframe with marker sizes sorted by humidity.  
* Narrowed down the city data dataframe to an ideal city data frame filtered by ideal weather conditions.
* Created a copy of the ideal city data dataframe named hotel dataframe that includes an extra column to store the name of the nearest hotel within a 10,000m radius.  
* Using Geoapify API, found the first hotel located within 10,000m of cities listed in the hotel dataframe, based on longitude and latitude.  
* Craeted a map plot of all cities within the hotel data frame with marker sizes sorted by humidity, and that additionally hovers hotel name and country over each marker.