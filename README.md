# World_Weather_Analysis

## Deliverable 1: Retrieve Weather Data

![WeatherPy_DB](https://user-images.githubusercontent.com/107448172/183552229-adb3acb4-8e48-4d54-a6d7-698b486f8ec7.png)

In this deliverable, we created a set of 2,000 random latitudes and longitudes. Then, we performed an API call with the OpenWeatherMap. With all the outcome, we add everything into a DataFrame which resulted into the table above with 709 cities around the world with their max temperature, humidity, cloudiness, wind speed and current description. 


## Deliverable 2: Create a Customer Travel Destinations Map 

![WeatherPy_vacay_DB](https://user-images.githubusercontent.com/107448172/183553174-ff3b3543-e080-44f5-90b6-0e8738270af5.png)

In this deliverable, we allocated all the destination hotel that match with customer input min and max temperature preferences.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/107448172/183554741-53d6ef57-e649-4fcc-981c-fac3861c2954.png)

Using a new generated DataFrame based on minimum and maximum temperature with empty rows are dropped, we created a marker layer map with pop-up markers which displayed hotel name, city, country, and current weather description with the maximum temperature.


## Deliverable 3: Create a Travel Itinerary Map 

<img width="856" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/107448172/183553806-d0befd72-2c3d-452a-9399-26714f7279be.png">

An itinerary has been created: 
- Start at: Ramada Hotel & Suites by Wyndham Ballina Byron in Ballina, AU with clear sky and max temp at 66.02F
- First stop: Bay Retreat Motel in Victoria Point, AU with clear sky and max temp at 67.02F
- Second stop: Shelly Bay Resort in Hervey Bay, AU with broken clouds and max temp at 72.01F
- Third stop: Kobbers Motor Inn Dalby in Dalby, AU with broken clouds and max temp at 67.68F
- Finish at: Ramada Hotel & Suites by Wyndham Ballina Byron in Ballina, AU with clear sky and max temp at 66.02F
