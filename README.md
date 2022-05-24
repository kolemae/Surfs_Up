# Weather Analysis for a Surf Shop
Project using Pandas, SQLAlchemy, and Jupyter Notebook to extract, analyze, format, and display weather data useful for client wanting to open a surf and ice cream shop.

## Table of contents
* [Overview of Project](#overview-of-project)
* [Results](#results)
* [Summary](#summary)

### Resources
- Data source: hawaii.sqlite
- Software: SQLAlchemy, Python 3.7.11, Jupyter Notebook

## Overview of Project
My client wants to open a surf and ice cream shop on Oahu, Hawaii. Using weather data and SQLAlchemy I was able to extract temperature, frequency of temperature, precipitation, and other useful data for them and their investors.

- Precipitation statistics for Oahu

![Precipitation](/Resources/precipitation.png)

- Temperature Frequency over the course of 12 months

![Temperature Frequency](/Resources/temp_frequency.png)

## Results
To address concerns about year-round operability I extracted temperature data for the months of June and December to compare and contrast.

June                       |  December
:-----------------------------------:|:-----------------------------------:
![June](/Resources/june_temps.png) |  ![December](/Resources/december_temps.png)

- The largest difference is seen in minimum temperatures, with June and December at a difference of 8°F
- Luckily maximum and mean temperatures are quite close, with differences of 2°F and 3.90°F respectively
- Temperatures above the 1st quartile for June sit nicely in the 70s
- Temperatures above the 1st quartile for December are 69°F or higher

## Summary
Overall temperatures and precipitation seen on Oahu, Hawaii indicate fair-weather for surfing and eating ice cream. Additional queries could be made into wind speed and wind duration since these affect the size of waves and could also help determine which customer surf level to cater to through the months.
