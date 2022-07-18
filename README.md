# World Weather Analysis
![](/Resources/map.jpg?raw=true=250x250)
### Purpose
Allows clients to input info about location and average weather temperature to identify potential travel locations and nearby hotels. Users are then prompted to choose up to four cities to create a travel itinerary, which is then plotted using the Google Maps API. 

### Technology Used: 
- Python
    - Pandas
    - Numpy
    - Citipy
- OpenWeatherMap API
- JSON
- Google Maps Direction API

### [Deliverable 1](/Weather_Database/Weather_Database.ipynb)
- Retrieve all of the following information from OpenWeatherMap API call:
    - Latitude and longitude
    - Maximum temperature
    - Percent humidity
    - Percent cloudiness
    - Wind speed
    - Weather description (for example, clouds, fog, light rain, clear sky)
- Add the weather data to a new DataFrame and export it as WeatherPy_Database.csv into the Weather_Database folder 


### [Deliverable 2](/Vacation_Search/Vacation_Search.ipynb)
- Input statements are written to prompt the customer for their minimum and maximum temperature preferences.
- A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.
- The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped. 
- The data is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv.
- A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information:
    - Hotel name
    - City
    - Country
    - Current weather description with the maximum temperature

### [Deliverable 3](/Vacation_Itinerary/Vacation_Itinerary.ipynb)
- Four DataFrames were created, one for each city on the itinerary.
- The latitude and longitude pairs for each of the four cities were retrieved.
- A DataFrame that contains the four cities on the itinerary was created.
- A marker layer map with a pop-up marker for the cities on the itinerary was created, and it was uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information:
    - Hotel name
    - City
    - Country
    - Current weather description with the maximum temperature


### File Descriptions
- WeatherPy_Database.csv (Weather API DataFrame details)
- WeatherPy_vacation.csv (Vacation locations with temperature range, hotels)
- WeatherPy_vacation_map.png (marker layer map)
- The Vacation_Itinerary.ipynb file (itinerary for each city) 
- The WeatherPy_travel_map.png image (directions layer map between the cities and the travel map )
- The WeatherPy_travel_map_markers.png image (marker layer map with a pop-up marker for the cities on the itinerary)