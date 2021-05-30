# World Weather Analysis


### Resources
**Source of Data** : citipy.py, worldcities.csv, Google Weather API, Open Weather API 

**Software** : Python 3.7.6 , Jupyter Notebook, Visual Studio Code.

##  Summary
  
### WeatherPy_Database
The objective of the challenge is to essentially refactor code we wrote in “VacationPy” and “WeatherPy” to add a description of the weather. In “Weather_Database.ipynb” we created a database that held latitude and longitude, maximum temperature, percent humidity, percent cloudiness, and wind speed. These metrics of measurement were already added in “WeatherPy.ipynb” so all that was needed was to add on a “Current Description” metric.  

### Vacation_Search

“Vacation_Search” is much like “VacationPy” in that we are looking not only for location and weather but also using Google API to look for suitable hotels in the locations we would eventually deem suitable based on weather. The difference once again is the inclusion of a “Current Description”  metric which marks how the weather would be in each given location. 

### Vacation_Itinerary

“Vacation_Itinerary.ipynb” dives into something new by utilizing Google Directions API to not only find the suitable weather and hotels but also the paths between cities by biking, walking, or driving. In this example four cities of Great Britain were chosen to represent the map markers and directions. The starting and ending city was Margate, then Oxford, followed by Newport, and finally Northam. The popup description lists the names of hotels, the city, country, and weather description which was created in the first two notebooks. It is important to note that failure in the first two notebooks would have resulted in failure of the last “Vacation_Itinerary” notebook so it is imperative that the syntax of the first two be perfect. 




