# World_Weather_Analysis

## Poject Overview

During this project I apply the recently aquired API knowledge, to retrieve weather information from a cities DataFrame. I was also able to update and introduce user inputs to then filter the data frame and display the results in a Map with pointers on each city describing the weather and a nearby hotel. To retrieve the nearby hotel I used the Google API to retrieve any lodging in a radius of 3,000 miles. Also I was able to create and display a map showing the route between 4 cities that the user could take to visit each city. 

In the development of the project I was able to understand the concept of APIs and how they work. I was able to make requests and retrieve specific data from the JSON file. I was also able to investigate and look at oficial documentation to understand the use and querys of the APIs I was using.

## Results

### Cities CSV

Using the random generated coordinates, I retrieved the closest city to each coordinate with the citypy module. Then, I retrieved the weather information of each city with the OpenWeather API and converted it into a DataFrame to then export the information to a CSV file.

### Vacation Map

I filtered the CSV file with cities that had a Maximum temperature between 75 and 90 degrees. Using Gmaps, I created a map that contained a marker in each city of the CSV that contained a small weather description and a nearby hotel.

![WeatherPY_vacation_map](https://user-images.githubusercontent.com/95836718/153731650-460a4472-d9ef-489a-8cdc-4e4ebed6389f.png)

### Itinerary Map

A direction Map was created showing the route between Lompoc, Lamont, Fresno and San José. This layer was created with the gmaps.directions_layer module. 

![WeatherPy_travel_map](https://user-images.githubusercontent.com/95836718/153731752-021c6aef-3cce-4e13-9585-01735581c94c.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/95836718/153731753-b4c52e57-456e-4960-9821-e1a99445f3d2.png)
