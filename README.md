# Web Visualization Dashboard [part 2 of Python-API project](https://github.com/ovinueza/Python_APIs)

Click [here](https://ovinueza.github.io/Web_Visualization_Dashboard/) to go to the web visualization dashboard


## Background
Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. 
This project highlights how we can obtain and interpret information quickly thanks to Python requests, APIs, and JSON 
This example anwers one simpel question: "What's the weather like as we approach the equator?"
Now, we know what you may be thinking: "Duh. It gets hotter..."
But, if pressed, how would you prove it?



## Task
This is the second part of [Python-API](https://github.com/ovinueza/Python_APIs)

After creating a Python script, on part 1, to visualize the weather of 500+ cities across the world of varying distance from the equator. We want to post the result quickly. So rather than using JavaScript to create other graphs, we add jpgs from the Python/Matplotlib Script into a Web Dashboard.

The results include:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

This project highlights the manipulations of CSS and HTML componets of a Web Page

## Findings
Based on the analyzed data there is no relationship between latitude and cloudiness.
<p align="center">
  <img width="320" height="200" src="https://github.com/ovinueza/Web_Visualization_Dashboard/blob/master/WebImages/CityLatitude_vs_Cloudiness.png">
</p>

Most of the cities located along the equator have high humidity during the summer.

Cities that have similar latitudes may differ greatly in their levels of humidity, based on how close they are to the ocean and other large bodies of water.

<p align="center">
  <img width="320" height="200" src="https://github.com/ovinueza/Web_Visualization_Dashboard/blob/master/WebImages/CityLatitude_vs_Humidity.png">
</p>

Based on data collected in mid July, cities along the equator and 20 degrees latitude have high temperatures, but cities in between the 18 to 42 degree latitudes have the highest temperatures. This may be due to the summer season and geographical location.

<p align="center">
  <img width="320" height="200" src="https://github.com/ovinueza/Web_Visualization_Dashboard/blob/master/WebImages/CityLatitude_vs_MaxTemp.png">
</p>

There is not a strong relationship between windspeed and latitude, with most cities having windspeed below 10 mph. The few cities with windspeeds above 20 mph may be in geographical areas where those speeds are common or are experiencing significant weather events. 

<p align="center">
  <img width="320" height="200" src="https://github.com/ovinueza/Web_Visualization_Dashboard/blob/master/WebImages/CityLatitude_vs_WindSpeed.png">
</p>





