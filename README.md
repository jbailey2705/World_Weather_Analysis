# World_Weather_Analysis

## Overiview
Travel and tourism provides individuals the opportunity to see the rest of the world outside the are they currently reside in. Certain instances occure that will have an impact on the decision one makes before traveling abroud, weather. Weather has a travel implications on whether or not individuals decide if travel is an option at a particular time.

The purpose of this project is to collect, analyze and visualize weather data across cities worldwide. We will provide travelers with a tool that will help  them determine their travel destination based on weather conditions across the world.

### Resources used to Compile the data
CSV files:
- [WeatherPy_Database.csv](https://github.com/jbailey2705/World_Weather_Analysis/files/9592210/WeatherPy_Database.csv)
- [cities.csv](https://github.com/jbailey2705/World_Weather_Analysis/files/9592219/cities.csv)

Python: Python v3.7.6, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON Traversals

## Weather Database
With a random set, 2,000 latitudes and longitudes were generated, an API call was also made on current weather data for the nearest corresponding cities.

API call used to retrieve the following data:

- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Current Weather description

## Vacation Search
Based on travelers criteria, weather preferences was taken into account inorder to generate a map with a list of destinations and hotel accomindations.

## Travel Destination example

![Screen Shot 2022-09-17 at 10 53 21 AM](https://user-images.githubusercontent.com/109354592/190868880-32cb91a6-f23d-40e7-a4a6-030a1cf21270.png)

## Vacation Itnerary
Google Directions API, sample itinerary was generated showing the route around cities in Margate.

![Screen Shot 2022-09-17 at 11 46 01 AM](https://user-images.githubusercontent.com/109354592/190869045-a660366d-d8f8-4a94-bde3-01be8aab0014.png)

## Statistical Analysis
City data was plotted, & linear regression used to show the relationships for the below variables:
- Lat. and Maximum Temperature
- Lat. and Humidity
- Lat. and Cloudiness
- Lat. and Wind Speed

### Scatter plots produced.
Scatter plots were created for each weather parameter against, latitude for all cities to show how different weather parameters change based on latitude.

![Fig1](https://user-images.githubusercontent.com/109354592/190869261-6ab0fbd1-2656-4c42-8e59-31f6f50150a5.jpeg)
![Fig2](https://user-images.githubusercontent.com/109354592/190869262-5cd27cd5-4e92-48b8-828c-19523c8c523a.jpeg)
![Fig3](https://user-images.githubusercontent.com/109354592/190869263-183187b0-1581-4689-b5eb-0336fe7959f8.jpeg)
![Fig4](https://user-images.githubusercontent.com/109354592/190869264-d674d926-1093-4a95-8418-defaa1c92f12.jpeg)

## Linear Regression: Northern and Southern Hemispheres
Performed Linear regression for the Northern and Southern Hemispheres, on four weather parameters: maximum temperature, humidity, cloudiness, and wind speed.

### Max Temp & Humidity

![Screen Shot 2022-09-17 at 12 51 26 PM](https://user-images.githubusercontent.com/109354592/190870205-f17cc455-1307-4f50-b9d1-14b3b9d54ec9.png)
![Screen Shot 2022-09-17 at 12 51 38 PM](https://user-images.githubusercontent.com/109354592/190870207-06d90537-d260-4de0-bf5a-1a36eae37e8a.png)
![Screen Shot 2022-09-17 at 12 51 48 PM](https://user-images.githubusercontent.com/109354592/190870209-a031c94d-0b6f-4be7-aa36-94e163b7d9e7.png)
![Screen Shot 2022-09-17 at 12 51 57 PM](https://user-images.githubusercontent.com/109354592/190870211-61c4d41b-87fd-4362-8fa2-40105cc7165b.png)

### Percent of Cloudiness & Wind Speed

![Screen Shot 2022-09-17 at 12 52 10 PM](https://user-images.githubusercontent.com/109354592/190870248-f7ea0f79-fc90-4042-a42a-b34691a9416c.png)
![Screen Shot 2022-09-17 at 12 52 20 PM](https://user-images.githubusercontent.com/109354592/190870250-863bd648-7f53-4de9-97f0-adce54bb4a7d.png)
![Screen Shot 2022-09-17 at 12 52 30 PM](https://user-images.githubusercontent.com/109354592/190870251-59692ac2-7443-412f-8608-038c767e264e.png)
![Screen Shot 2022-09-17 at 12 52 37 PM](https://user-images.githubusercontent.com/109354592/190870252-7988d20a-2666-47a0-b8a2-0ccad1897ce3.png)


