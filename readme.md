# Weather Data  Aggregator & Analysis Project


## Introduction

The Weather Data Analysis Project aims to analyze weather patterns and trends over a specific period. By utilizing historical weather data, we can gain insights into climate changes, predict future weather conditions, and make data-driven decisions.

## Objectives

- Analyze weather data.
- Identify trends and patterns in temperature, humidity, speed, and other weather variables.
- Provide visualizations to represent the data effectively.

## Data Collection

- Used Public Openweathermap API key to fetch Live Weather data overall Maharashtra State for Analysis


### Description

The dataset includes the following variables:

- name: The name of the city.
- weather: The type of climate in that city eg(cloudy, rain).
- humidity: The level of humidity.
- Wind: The level of wind.
- speed: The level of humidity.
- ground_level: Shows the Level of ground level pressure
- dt: The Date & time of the data logged
- hour: The Specific Hour column for time series analysis

## Methodology

1. **Data Gathering**: Gathering the overall weather Data and store into SQlite3 server.
2. **Data Analysis**: Use statistical methods to analyze the gathered data.
3. **Visualization**: Create graphs and charts to illustrate trends.

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Platform**: Jupyter Notebook


## Setup & Run
- Store all the files in single folder.
- Run the Task Weather Python.py
- If dataset file (weather_data.db) not created by default. Then manually create the "weather_data.db"
- Then analyze the data you fetched

## Note 
-  Make Sure you run the functions to get the Output. 


<img src="images/Humidity Trend.png"></img>
