# World_Weather_Analysis
### Purpose of Repository
In this Repository we created 3 folders **Weather_Database, Vacation_Search and Vacation_Itinerary**.
  

###### Weather_Database
    
In this folder we import the **2000** different cities through the **latitude and longtitude** with the use of **Weather API key** and **convert** that city weather list into the **DataFrame**. After converting that list in DataFrame we convert that DataFrame into the **.CSV** file name as **WeatherPy_Database**.
    
    
###### Vacation_Search

In this folder we import the **.CSV file From the Weather_Database** folder and use that csv file **retrive the city data based on the minimum and maximum temprature.** After that we **added the new column into the list Hotel Name** and converted that **DataFrame into the .CSV file** name as **Weather_Vacation.CSV.** After that we applying the formatting on that data and **retrive CityName,CountryCode,Weather Description and Temprature info** column and create MarkerLayer Map with the use of Latitude and Longtitude and formatted coulmn which pop up the markers and description on each marker. Image save as **WeatherPy_Database_map.png**


###### Vacation_Itinerary

In this folder we import the **.CSV file From the Vacation_Search** folder and use that csv file as **WeatherPy_Database** and create MarkerLayer Map with the use of Latitude and Longtitude then select perticular Cities for Vactions and add that destinations in the map, use the g_key and assign the route and shows that route on Map name as **Weather_Travel_map.png**. At the end create the Marker map and shows the markers on travel map image as name **Weather_Travel_map_Markers.png**.



  
  

   
