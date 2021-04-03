# World_Weather_Analysis

# Overview
The main purpose thiupdate PlanMyTrip app and to take it to the possible next level.
First, we add weather descriptin to the weather data  we retrived by using lattitude and longtuide coardinates.
Secon, we prompt input statment to use a beta tester to fillter weather preferences.Third, 
using weather preference information we identify potential tourist destinationss and nearby hotels. 
Finally, we create a travel route between selected tour cities and we also create a marker layer map using the Google Maps Directions API.
## Result
### Retrieve Weather Data
Using a set of 2000 random latitudes and longitudes coardinate we 
retrive nearby cities and weather data using an API call.
Using the openweathermap we retrived the current weather 
description and created the below dataframe.


![WeatherPY_Dataframe](https://user-images.githubusercontent.com/78656720/113492793-2a4c6b80-94a8-11eb-82ba-22b65a4140a9.png)

### Cutomer Travel Destinarions
Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/78656720/113492947-4dc3e600-94a9-11eb-9966-9666c60f8459.png)
