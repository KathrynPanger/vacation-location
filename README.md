
## Summary:

**WeatherPy**<br/><br/>
This project analyzes the relationship between distance from the equator and various weather features using data from the OpenWeather API. Data is collected for 500 global cities and then regressed and analyzed for patterns in data features. 

**VacationPy**<br/><br/>
This project uses the data above to identify ideal vacations spots by identifying places with low windspeed and cloudiness, creating a heat map to display humidity, identifying hotel locations in desireable cities, and creating an interactive map to display details for locations and hotels. This is done using the Google Places API.


## The Files:
```
|+-- VacationPy 
|   +--VacationPy.ipynb -> Main project code: retrieves cities, builds maps, identifies ideal vacation spots
|    |   +--worldcitiespop
|        |   +--worldcitiespop_reduced.csv -> CSV file of world cities
|+--WeatherPy
|   +--WeatherPy.ipynb -> Main project code: retrieves weather data, performs regressions, and displays analysis
|    |   +--WeatherPy_dvswap.ipynb -> Same code, but IV and DV swapped to be more intuitive (was not necessary for simple linear regression analysis)
```

## A Few Vizualization Samples:


 ![Vizualization Preview](charts/regression_T_b.png)
 ![Vizualization Preview](charts/regression_Humidity (%)_b.png)
 ![Vizualization Preview](charts/regression_W_n.png)
