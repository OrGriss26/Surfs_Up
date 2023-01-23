# Surfs_Up

Analyzing weather data in jupyter notebook.
This analysis project requires a quick build, quick turnaround data frame that pulls information from available Hawaiian Weather sites.
Advanced Data Storage and Retrieval with Jupyter Notebook, SQLite and SQLAlchemy.

## Overview of the Surfs Up Analysis

This project explores the power of Advanced Data Storage and Retrieval to efficently produce an analyis of temperature trends in Oahu, Hawaii. Specifically, summary statistics of temperature data were requested for the months of June and December, in order to determine if a prospective surf and ice cream shop business can sustainably operate year-round as opposed to a seasonal business.
An investor wants to learn more about the weather before committing to build a Surf and Ice Cream shop in Oahu, Hawaii. The investor's main concern is the precipitation forcing the shop to close too frequently. To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database.

## Porpuse

The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method.

This analysis is to help W. Avy, a famous surfer and investor make important business decisions about opening an ice cream shop with surf gear, called "Surf n' Shake Shop" on the island of Oahu. The location is important because climate can vary on the island. W. Ivy wants to be prepared by knowing weather history and patterns in the area where the shop might be located. A perfect place for the shop is where there is the right balance of warm temperatures and sunny days throughout the year. The data-driven decisions that we will make will be based on temperature and rainfall for the past 7 years from 2010-2017, specifically June and December. These 2 months are far apart enough to ensure we have good conditions year-round.

  - The analysis consists of 2 parts:   
  1. Temperature Statistics analysis for June and December.
  2. Rainfall analysis for June and December.
  
- Explain the structures, interactions, and types of data of a provided dataset.
- Differentiate between SQLite and PostgreSQL databases.
- Use SQLAlchemy to connect to and query a SQLite database.
- Use statistics like minimum, maximum, and average to analyze data.
- Design a Flask application using data.

## Results

The results of the Surfs Up Analysis determined the following:

1. Based on count of 1,700 temperatures in the month of June over the course of seven years, the average temperature is calculated at 75 degrees, minimum of 64 degrees, and maximum of 85 degrees.

### June Statistics

![Pic_1](https://github.com/Baylex/surfs_up/blob/main/Resources/june_stat_temp_prcp.PNG)

2. Based on count of 1,517 temperatures in the month of December over the course of seven years, the average temperature is calculated at 71 degrees, minimum of 56 degrees, and maximum of 83 degrees.

### December Statistics

![Pic_1](https://github.com/Baylex/surfs_up/blob/main/Resources/june_stat_temp_prcp.PNG)

3. There are 183 more temperatures analyzed for June statistics than December statistics for the seven year period, however the amount of variance between the two data sets is relatively close to one another at 3.26 standard deviation (June) and 3.75 standard deviation (December).

## Summary

The investor's main concern was getting rained out too frequently. Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably close. The temperature data is not strongly skewed for either month. The ratio of the temperatures to the precipitation for the two months is also reasonably similar with few outliers over 3 inches of precipitation. The data supports opening a Surf and Ice Cream shop year-round.

### June

![Pic_1](https://github.com/Baylex/surfs_up/blob/main/Resources/june_stat_temp_prcp.PNG)

### December

![Pic_1](https://github.com/Baylex/surfs_up/blob/main/Resources/june_stat_temp_prcp.PNG)
