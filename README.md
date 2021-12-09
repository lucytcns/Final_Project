# Weather Analysis

## STA 141B Final
#### Group Members: Ziyu Tang, Keke Chien, Huifei Xu, Zhaoqiang Zhou

describes the project at a high level, what each code file does, where I can find the project notebooks, and how to get the data,

### Introduction
For thousands of years, people have been studying the dry and rainy seasons for agricultural planning and urban and rural construction. However, the time period of the dry and rainy season is not fixed. We believe that certain weather terms determine the dry and rainy season. Therefore, we want to analyze the factors show the changes in the rainy and dry seasons. We list four factors related to the dry and rainy seasons as variables: humidity, air pressure, wind speed, and temperature. 

According to the topic, we have two following questions from time and place as starting points:

For different locations at a fixed time, what is the difference between the dry and rainy seasons in different areas? In order to avoid little difference between the dry and rainy seasons in the same climate region, we choose cities in five different climate regions in the United States from 2016 to 2020: Sacramento, Lake Tahoe, Las Vegas, Denver, and Indianapolis.

For fixed location at different times, is there any difference between the current and the past dry and rainy seasons? We choose Sacramento as the location for this question, and observe and compare the dry and rainy seasons of 1976-1980 and 2016-2020 Sacramento.


## Readme:
In this project, we want to analyze the factors show the changes in the rainy and dry seasons. We list four factors related to the dry and rainy seasons as variables: humidity, air pressure, wind speed, and temperature. According to the topic, we have two following questions from time and place as starting points: For different locations at a fixed time, what is the difference between the dry and rainy seasons in different areas? For fixed location at different times, is there any difference between the current and the past dry and rainy seasons? 

We think that studying the dry and rainy seasons is helpful to Water Conservancy Projects, such as drainage system construction and drinking water policy, etc. Understanding the time pattern of the dry and rainy season can enable people to have better countermeasures and guidelines for urban and rural construction.

..........

To see our complete analysis, read our notebook to know more.

## Data

### File Strucutures
#### Files
Data: Including aggregated weather data from 2016 to 2020 in five cities
- sacramento
- Denver
- Las_Vegas
- Lake_Tahoe
- Indianapolis

1976_80: Including weather related pictures from 1976 to 1980 at Sacramento
(Gathered from another source since we do not have data from 1976 to 1980 in metaweather.api)
- AirPressure.jpeg
- Humidity.jpeg
- Windspeed.jpeg
- Temperature.jpeg

Notebooks: Including all notebooks (code and report)
- WebScraping.ipynb: Including codes for aggregated weather data from 2016 to 2020 in five cities from metaweather.api. Specifically the data is aggregated based on daily average and transformdata to csv for better graphing
- Graphing: Including graphing codes for air pressure, humidity, windspeed, temperature for data packed from WebScraping
- Report: Including write-ups and output graphs

### Data Source
- https://www.metaweather.com/api/
- https://weatherspark.com/
