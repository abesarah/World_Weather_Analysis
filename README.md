# World Weather Analysis
![](/Resources/map.jpg?raw=true=250x250)
### Purpose
Allows clients to input info about location and average weather temperature to identify potential travel locations and nearby hotels. Users are then prompted to choose up to four cities to create a travel itinerary, which is then plotted using the Google Maps API. 

### Deliverable 1
Retrieved weather information from an API called OpenWeatherMap, and added to a new DataFrame.

### Deliverable 2
Prompted customers for their minimum and maximum temperature preferences, and a new DataFrame was created based on it. Hotel names corresponding to the temperature were retrieved and added to the DataFrame .
A marker layer map with pop-up markers for the cities in the vacation DataFrame was created, and was uploaded as a PNG. Each marker had the following information
- Hotel name
- City
- Country
- Current weather description with the maximum temperature

### Deliverable 3
Four DataFrames were created, one for each city on the itinerary.
The latitude and longitude pairs for each of the four cities were retrieved.
A DataFrame that contains the four cities on the itinerary was created.
A marker layer map with a pop-up marker for the cities on the itinerary was created, and it was uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information:
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