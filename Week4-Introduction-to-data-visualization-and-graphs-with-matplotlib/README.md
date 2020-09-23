<img src="assets/data-visualize-readme.png" align = "center">

# <div align="center">Introduction to Data Visualization and Graphs with Matplotlib</div>

## Recap
By this point, we have looked into important skills such as:
- **Getting started with Pandas**:
    - Importing Pandas library: We learned how to import built-in libraries into Python.
    - Loading datasets (.csv files): We learned how to load specific datasets to create a Pandas dataframe.
    - Setting an index: We learned how setting an index helps you to identify each entity with a meaningful index rather than pre-generated index numbers.
    - Getting basic info about dataframe: We used functions like head, describe, info, and columns to provide you a good insight into the dataframe.
- **Cleaning datasets**:
    - Removing NaN values: We discussed how to remove rows with NaN values by setting the specific criteria to remove NaN values.
    - Removing a column: If a column does not provide a meaningful insight, we now know how to remove the column.
    - Selecting subsets of data: We learned that you can select the columns to work with using column locations or column names.
    - Filtering rows based on criteria: We learned that based on your interest and project, you can set your own criteria to filter the dataset that meets the criteria.
    - Aggregation functions: We learned that with aggregate functions, you can easily identify overall trends of the dataset. These functions will help you to focus on more relevant/meaningful data rather than the whole data.

## Learning Objectives
For this week, our main focus will be to visualize our data when it's loaded in a Pandas DataFrame. For this, we will be using **matplotlib** and **pandas**. You are familiar with pandas by now but matplotlib is new to you. Therefore, understanding and using the tools provided through matplotlib will be our main focus. By the end of the week, you will be able to use and know the following ```skills```:
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
### Stock Market Index <img src="https://github.com/ShayanRiyaz/DigitalHistory/blob/master/Week4-Introduction-to-data-visualization-and-graphs-with-matplotlib/assets/wallstreet.png?raw=1" width="300" align="right">

This is a simple introductory dataset. The dataset contains has a shape of 5473 rows and 10 columns. The first row is the header row, therefore the shape of our dataset is (5472,10). The first column is the datetime ranging from 1990 to 2012. The remaining 9 columns are numerical values that indicate the stock prices of companies such as:
- AA 
- AAPL 
- GE 
- IBM 
- JNJ 
- MSFT 
- PEP 
- SPX 
- XOM

### California Housing Information <a name="CaliforniaHousing"></a>
<img src="https://github.com/ShayanRiyaz/DigitalHistory/blob/master/Week4-Introduction-to-data-visualization-and-graphs-with-matplotlib/assets/california.png?raw=1" width="300" align="right">

This dataset serves as an excellent introduction to implementing machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables, and is an optimal size datset for beginners.

The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

**Content**
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. The columns are as follows (their names are relatively self-explanatory):

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

### Malnutrition <a name="Malnutrition"></a>
<img src="https://github.com/ShayanRiyaz/DigitalHistory/blob/master/Week4-Introduction-to-data-visualization-and-graphs-with-matplotlib/assets/malnutrition.png?raw=1" width="300" align="right">

Malnutrition continues to be the reason for making children much more vulnerable to diseases and death.
So, we will analyze a datset regarding this pertinent topic. For context, there are 4 broad types of malnutrition: wasting, stunting, underweight and overweight.

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
Pandas stands for “Python Data Analysis Library." It was created by Wes McKinney, who built pandas to help work with datasets in Python for his work in finance at his place of employment.

According to the library’s website, pandas is “a fast, powerful, flexible and easy to use opensource data analysis and manipulation tool, built on top of the Python programming language.”

Pandas is designed to work with two-dimensional data (similar to Excel spreadsheets). Just as the NumPy library had a built-in data structure called an array with special attributes and methods, the pandas library has a built-in two-dimensional data structure called a DataFrame.



## Resources
- [Matplotlib.pyplot](https://matplotlib.org/3.3.0/api/_as_gen/matplotlib.pyplot.html)
- [Pandas plotting](https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.DataFrame.plot.html)
- [California Housing](https://www.kaggle.com/camnugent/california-housing-prices)
- [Malnutrition](https://www.kaggle.com/ruchi798/malnutrition-across-the-globe?select=malnutrition-estimates.csv)
- [Tableau Visualizations](https://public.tableau.com/profile/ruchi.bhatia#!/vizhome/MalnutritionAnalysis/MalnutritionAnalysis)

