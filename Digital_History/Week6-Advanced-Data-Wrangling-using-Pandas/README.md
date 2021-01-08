# Advanced Data Wrangling using Pandas

## Recap
In earlier weeks, we have covered the following concepts in Pandas:
- Load a file
- Set an index
- Get a basic info about dataset (```head```,```describe```, ```info```) 
- Remove NaN values / columns
- Select subsets of dataset
- Filter dataset based on criteria
- Aggregation functions

## Learning Objectives
This week, we will cover a more advanced data manipulation using Pandas. 

By the end of the week, you wil be able to implement the following functions and its applications:

- Series (create, sort, access, binary operations)
- Advanced Dataframe
  - Create new columns
  - Sort dataframe
  - Drop entities
  - Replace NaN values
  - Unique values
  - Join two dataframe

## About the Libraries
### Pandas

<img src="https://github.com/bitprj/DigitalHistory/blob/Narae/Week3-Introduction-to-Open-Data-Importing-Data-and-Basic-Data-Wrangling/assets/icons/pandas.png?raw=1" width="200" align="center"> 

Pandas stands for **Python Data Analysis Library**. Pandas is an open source data analysis and manipulation tool and it is widely used both in academia and industry. It is built on top of the Python programming language and it offers data structures and operations for manipulating numerical tables and time series.
 

## About the Dataset 
### January Flight Delays

<img src="https://github.com/bitprj/DigitalHistory/blob/Narae/Week6-Advanced-Data-Wrangling-using-Pandas/assets/icons/flight.jpg?raw=1" width="300" align="center"> 

We will be using the flight delay dataset for January 2020. 

This data is collected from the Bureau of Transportation Statistics, Govt. of the USA. This data is open-sourced under U.S. Govt. Works. This dataset contains all the flights in the month of January 2020. There are more than 400,000 flights in the month of January itself throughout the United States. The features were manually chosen to do a primary time series analysis. There are several other features available on their website.

This data could well be used to predict the flight delay at the destination airport specifically for the month of January in upcoming years as the data is for January only.

- Day_of_week: Day of Week starting from Monday
  - Ex: Monday = 1, Sunday = 7
- Op_unique_carrier: Unique Carrier Code (DL, WN, AA, 9E, OO, etc.)
- Origin: Origin Airport (JFK, ATL, SFO, LAX, etc.)
- Dest: Destination Airport (JFK, ATL, SFO, LAX, etc.)
- Dep_time: Actual Departure Time (local time: hhmm)
  - Ex: 1848 is 18:48 in local time
- Dep_del15: Departure Delay Indicator, 15 Minutes or More (1=Yes, 0=No)
- Arr_time: Actual Arrival Time (local time: hhmm)
- Arr_del15: Arrival Delay Indicator, 15 Minutes or More (1=Yes, 0=No)
- Cancelled: Cancelled Flight Indicator (1=Yes, 0=No)
- Diverted: Diverted Flight Indicator (1=Yes, 0=No)
- Distance: Distance between airports (miles)



## For further assistance

If you would like to learn more about Pandas dataframe, here's the resource you can refer to. Pandas Dataframe API is a library where all of the functions and properties in Pandas are available.

[Pandas Dataframe API](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)