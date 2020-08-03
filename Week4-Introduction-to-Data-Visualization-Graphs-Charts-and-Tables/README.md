# Introduction to Data Visualization

## Recap
By this point we have looked into some important steps such as:
- Opening a google co-lab notebook.
- Importing libraries such as Pandas and Numpy.
- Loading datasets (.csv files).
- Observing datasets as pandas DataFrame.

## About the Datasets

### Stock Market Index

### California Housing Information
This dataset serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and sits at an optimal size between being to toyish and too cumbersome.

The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

**Content**
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. The columns are as follows, their names are pretty self explanitory:

- longitude
- latitude
- housingmedianage
- total_rooms
- total_bedrooms
- population
- households
- median_income
- medianhousevalue
- ocean_proximity

## Learning Objectives
For this week our main focus will be to visualize our data when it's loaded in a Pandas DataFrame. For this we will be using **matplotlib** and **pandas**. You are familiar with pandas by now but matplotlib is new to you. Therefore, understanding and using the tools provided through matplotlib will be our main focus. By the end of the week you wil be able to implement the following ```commands```:
- Understand how  ```pyplot``` works and how to you can make customized plots using it.
- Use ```pandas``` to plot your dataFrame and map columns in the form of useful visualizations.
- Learn how to load and use Time-Series data using Pandas ```pd.read_csv```
- Use the 'Stock market data' to learn how to plot basic graphs and making them readable by adding:
  - colors
  - markers
  - linestyles
  - labels
  - ticks
  - legends
- Use ```matplotlib``` to create bar plots,line charts and scatter plots.
- Loading and Examining the California Housing dataset and mapping geo-location data:
  - Visualizing the distribution of median income of home owners in California.
  - Comparing the median income with the price of the houses.
  - Find Dense clusters using visualization techniques.

## About the Libraries
### Matplotlib

### Pandas
Pandas stands for “Python Data Analysis Library”.It was created by Wes McKinney, who built pandas to help work with datasets in Python for his work in finance at his place of employment.

According to the library’s website, pandas is “a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.”

Pandas was designed to work with two-dimensional data (similar to Excel spreadsheets). Just as the NumPy library had a built-in data structure called an array with special attributes and methods, the pandas library has a built-in two-dimensional data structure called a DataFrame.



## Resources
- [California Housing](https://www.kaggle.com/camnugent/california-housing-prices)

