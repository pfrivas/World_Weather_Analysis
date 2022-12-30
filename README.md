# World_Weather_Analysis

## Project Overview

Users will use the PlanMyTrip app to identify potential travel destinations and nearby hotels around the globe with their desired weather prefrences and be able to pick cities from the potential travel destinations in order to create a travel itenerary and a travel route between the picked cities.

## Resources

**Software:** Python 3.11, Anaconda, Jupyter Notebook

**Code:** [Weather Database](https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Weather_Database/Weather_Database.ipynb), [Vacation Search](https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Search/Vacation_Search.ipynb), [Vacation Itinerary](https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Itinerary/Vacation_Itinerary.ipynb)

**Data Sources:** 
- [Citipy](https://github.com/pfrivas/World_Weather_Analysis/tree/main/World_Weather_Analysis/Resources/citipy)
- [Cities Database](https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Resources/cities.csv)
- [Vacation Database](https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Search/WeatherPy_vacation.csv)
- [Weather Database](https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Weather_Database/WeatherPy_Database.csv)
- [Open Weather Maps API](https://openweathermap.org/current)
- [Google Maps and Places API](https://developers.google.com/maps/documentation/places/web-service/search)
- [Google Maps and Directions API](https://developers.google.com/maps/documentation/directions/overview)

## Results

### Weather Data Retrieval

Using the Open Weather Map API, weather data (Maximum Temperature, Cloudiness, Wind Speed, Humidity, and Current Weather Description) from over 600 cities globally was retrieved in order to make it easy for users to determine desired travel destinations

<img src = https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Search/WeatherPy_vacation_map.png>

### Customer Travel Destinations Map

Using the user's desired weather preferences, the gmaps plugin software showed travel destinations with the weather preferences generated using the [Google Maps and Places API](https://developers.google.com/maps/documentation/places/web-service/search) app. The image below shows the randomly generated destinations with the weather information as well as a hotel name for each location.

<img src = https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Itinerary/WeatherPy_travel_map_markers.png>

### Travel Itenerary Map

A travel itenerary between 4 cities seleced by the user was generated using the [Google Maps and Directions API](https://developers.google.com/maps/documentation/directions/overview) app. In the image below a travel itenerary was created with the South American cities Caravelas, Santiago Del Estero, La Macarena, and Tambopata.

<img src = https://github.com/pfrivas/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Itinerary/WeatherPy_travel_map.png>
