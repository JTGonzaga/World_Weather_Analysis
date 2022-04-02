# World_Weather_Analysis
## Overview
  Initially, the purpose of this analysis was to use API's in order to analyze the weather. This soon turned in to utilize the information to choose ideal vacation spots around the world based on set paramaters
## Weather Database
  Using Open Weather Map's API, I was able to gather data on cities around the world using randomly generated coordinates and using python to find information provided through .json files. This information was then formatted to display the different weather conditions of over 700 cities around the world. The weather conditions include: Max Temp, % Humidity, % Cloudiness, and Wind Speed. 
## Vacation Search
   In order to maximize customer satisfaction, the customer is given an option to choose locations based on weather prefrence. In this example, the customer chose a minimum temperature of 75 degrees and a maximum temperature of 90 degrees. These parameters provided hundreds of different cities so the next step was to narrow it down and only display cities that had hotels within 5000 meters of the selected coordinates. Once these cities were chosen, the final step is to plan the trip. Below is an example of the different cities in the US that were within the requested parameters.
![Vacation Search](https://github.com/JTGonzaga/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)
## Vacation Itinerary
  Google's maps is useful to find locations, but without adding the Directions API it's much harder to plan efficient routes during a trip. After settling on four cities to travel to, the next step is to find directions. Utilizing the same map as before, I was able to add information for each marker and also get directions to travel to every stop in one trip.
![Vacation_Markers](https://github.com/JTGonzaga/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
![Vacation Directions](https://github.com/JTGonzaga/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
