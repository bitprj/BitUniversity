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
  - Unique values
  - Join two dataframe

## About the Libraries
### Pandas

Pandas is an open source data analysis and manipulation tool, built on top of the Python programming. Anytime you work with data, you can use Pandas and you will be able to answer any questions.
 

## About the Dataset 
### January Flight Delays

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