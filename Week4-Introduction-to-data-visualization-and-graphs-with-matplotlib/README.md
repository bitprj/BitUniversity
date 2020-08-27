<img src="assets/data-visualize-readme.png" align = "center">

# <div align="center">Introduction to Data Visualization and Graphs with Matplotlib</div>

## Recap
By this point, we have looked into some important steps such as:
- Opening a google co-lab notebook.
- Importing libraries such as Pandas and Numpy.
- Loading datasets (.csv files).
- Observing datasets as pandas DataFrame.

## Learning Objectives
For this week our main focus will be to visualize our data when it's loaded in a Pandas DataFrame. For this, we will be using **matplotlib** and **pandas**. You are familiar with pandas by now but matplotlib is new to you. Therefore, understanding and using the tools provided through matplotlib will be our main focus. By the end of the week you will be able to implement the following ```commands```:
- Understand how  ```pyplot``` works and how you can make customized plots using it.
- Use ```pandas``` to plot your dataFrame and map columns in the form of useful visualizations.
- Learn how to load and use Time-Series data using Pandas ```pd.read_csv```
- Use the 'Stock market data' to learn how to plot basic graphs and making them readable by adding:
  - colors
  - markers
  - linestyles
  - labels
  - ticks
  - legends
- Use ```matplotlib``` to create bar plots, line charts and scatter plots.
- Loading and Examining the California Housing dataset and mapping geolocation data:
  - Visualizing the distribution of median income of homeowners in California.
  - Comparing the median income with the price of the houses.
  - Find Dense clusters using visualization techniques.

## About the Datasets
### Stock Market Index

This is a simple introductory dataset. The dataset contains has a shape of 5473 rows and 10 columns, the first row is the header row, therefore the shape of our dataset is (5472,10). The first column is the datetime ranging from 1990 to 2012. The remaining 9 columns are numerical values that indicate the stock prices of companies such as:
- AA 
- AAPL 
- GE 
- IBM 
- JNJ 
- MSFT 
- PEP 
- SPX 
- XOM

### California Housing Information
This dataset serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and sits at an optimal size between being to toyish and too cumbersome.

The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

**Content**
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. The columns are as follows, their names are pretty self explanatory:

- longitude
- latitude
- housing median age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- median house value
- ocean_proximity

### Malnutrition
Malnutrition continues to be the reason for making children much more vulnerable to diseases and death.
There are 4 broad types of malnutrition: wasting, stunting, underweight and overweight.

- Severe Wasting - % of children aged 0–59 months who are below minus three standard deviations from median weight-for-height
- Wasting – Moderate and severe: % of children aged 0–59 months who are below minus two standard deviations from median weight-for-height
- Overweight – Moderate and severe: % aged 0-59 months who are above two standard deviations from median weight-for-height
- Stunting – Moderate and severe: % of children aged 0–59 months who are below minus two standard deviations from median height-for-age
- Underweight – Moderate and severe: % of children aged 0–59 months who are below minus two standard deviations from median weight-for-age

Which countries bear the greatest share of all forms of malnutrition?
% of stunted, overweight and wasted children under 5, by country income classification

## About the Libraries

### Matplotlib
The matplotlib Python library, developed by John Hunter and many other contributors, is used to create high-quality graphs, charts, and figures. The library is extensive and capable of changing very minute details of a figure.

### Pandas
Pandas stands for “Python Data Analysis Library”.It was created by Wes McKinney, who built pandas to help work with datasets in Python for his work in finance at his place of employment.

According to the library’s website, pandas is “a fast, powerful, flexible and easy to use opensource data analysis and manipulation tool, built on top of the Python programming language.”

Pandas is designed to work with two-dimensional data (similar to Excel spreadsheets). Just as the NumPy library had a built-in data structure called an array with special attributes and methods, the pandas library has a built-in two-dimensional data structure called a DataFrame.



## Resources
- [Matplotlib.pyplot](https://matplotlib.org/3.3.0/api/_as_gen/matplotlib.pyplot.html)
- [Pandas plotting](https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.DataFrame.plot.html)
- [California Housing](https://www.kaggle.com/camnugent/california-housing-prices)
- [Malnutrition](https://www.kaggle.com/ruchi798/malnutrition-across-the-globe?select=malnutrition-estimates.csv)
- [Tableau Visualizations](https://public.tableau.com/profile/ruchi.bhatia#!/vizhome/MalnutritionAnalysis/MalnutritionAnalysis)

