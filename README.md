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

### Vacation Search

By using  input statment we retrive cities that are according to cusomer preferencs.We also idetify potential tourist destinations and the nearby hotels. Finally, with use a a marker layer map with pop-up markers to show cities with the weather descriptin, maximum and minumum tepratures and nearby hotels.
The below table and chart shows the detail of the app.

![Hotel_df](https://user-images.githubusercontent.com/78656720/113493125-ba8bb000-94aa-11eb-8eb5-2ff7795240cf.png)

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/78656720/113492947-4dc3e600-94a9-11eb-9966-9666c60f8459.png)

### Vacation Itinerary 
The third and final step of this project is to creat a travel itinerary that shows the travel route between the preffererd cities chosen from the customer’s possible travel destinations. Then, we create a pop-up marker for each city on the itinerary using the Google Directions API. The Below chart shows the detail of the app. 

![WeatherPy_travel_map](https://user-images.githubusercontent.com/78656720/113493267-dfccee00-94ab-11eb-866b-469f9bef0d12.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/78656720/113493303-1e62a880-94ac-11eb-9b0d-464a19851011.png)

## Summary
By generating random Latitudes and Longtiudes coardinates we retrive create a city dataframe, containing current weather description. Then Using the data frame and prompt input of cutomer preferences we created a data frame containing city, weather description, hotels name ,and we create a Customer Travel Destinations Map . Finally using the preferences of our cutomers we create a Travel Itinerary Map on selected cities and a pop-up marker for each city on the itinerary using the Google Directions API.



