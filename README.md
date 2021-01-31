# World_Weather_Analysis

This project had three deliverables related to gathering real-time weather data to provide the most updated travel information to our clients. This way, clients can make choices based on their preferences and we can build them an ideal travel itinerary. </br>

## Deliverable One

First, I generated a set of 2,000 latitudes and longitudes. I then used CityPy to retrieve the nearest city to each coordinate point and performed an API call with OpenWeatherMap. Finally I created a DataFrame to hold the weather data for each randomly generated city and a hotel clients could stay at. 

## Deliverable Two
The second deliverable includes client input on their weather preferences. This input then informs the travel destinations available to them with the given parameters. I showed all of the viable destinations on a marker layer map with pop-up markers that includes the city/country name, hotel name and real-time temperature data. I made a gmaps API call to create this map. 

## Deliverable Three
Finally, I created a travel ininerary map using another gmaps API (directions). I selected four cities that a client could access on the same trip that met their preferences. I built an itinerary and provided the client directions between all four locations. 
