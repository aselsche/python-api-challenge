**Python-Api-Challenge Summary**

In the Python API Challenege, I created a Python script to visualize the weather of 600+ cities across the world of varying distance from the equator. To accomplish this, I utlized Python library, the OpenWeatherMap API to create a representative model of weather across world cities.

The analysis of cities for Weatherpy can be found here: [Jupyter Notebook](WeatherPy/WeatherPy.ipynb) and the Heat map show casing the hotels can be found here: [Jupyter Notebook](VacationPy/VacationPy.ipynb).
![image](https://user-images.githubusercontent.com/84043141/126705954-faddce15-fe72-4980-826e-8406c1e8f058.png)

After building the data set of the cities, a series of scatter plots were built to showcase the following relationships:

    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude
    
**From the analysis, the following conclusions can be drawn:**

**Temperature (F) vs. Latitude**
As shown in Fig 1, Latitude vs. Temperature Plot,  which includes data for 600+ cities. The temp peaks at approx. 30-degree latitude currently.Temperature seems to have a clear correlation with latitude: farther from equator = colder. The weather is significantly warmer as one approaches the equator which is the line of 0 degrees latitude. 

**Humidity (%) vs. Latitude**
As you can see from the VacationPy notebook, the humidity is high across the world at this time of the year, summer, represented by the numerous red-colored regions on the heatmap representing maximum or near-maximum humidity. The values seem especially high in places near the oceans. As you can see from the Fig 2, there is no correlation between humidity (%) and latitude.
The heatmap was built to show the humidity across cities.
![image](https://user-images.githubusercontent.com/84043141/126704910-f2d50e40-ef74-4cba-b520-38703a7a2b05.png)

**Cloudiness (%) vs. Latitude**
The Cloudiness vs. Latitude plot shown below, containing data from all cities, does not seem to show a relationship between cloudiness and city latitude. However, there seem to be some values for cloudiness that the points cluster along, noticeably 0, 20, 40, 78, 90, and 100. 

**Wind Speed (mph) vs. Latitude**
The Wind speed vs. Latitude plot, shown below for all cities, does not seem to show any relationship between wind speed and latitude. Most of the wind speed values are below about 20 mph currently, with only a few values above that wind speed limit.
