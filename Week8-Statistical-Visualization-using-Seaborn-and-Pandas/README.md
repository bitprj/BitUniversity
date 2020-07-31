# Introduction to Data Visualization - DRAFT 2

## Recap
By this point we have looked into some important steps such as:
- Opening a google co-lab notebook.
- Importing libraries such as Pandas and Numpy.
- Loading datasets (.csv files).
- Observing datasets as pandas DataFrame.

## About the Datasets

### Tips
Food servers’ tips in restaurants may be influenced by many
factors, including the nature of the restaurant, size of the party, and table
locations in the restaurant. Restaurant managers need to know which factors
matter when they assign tables to food servers. For the sake of staff morale,
they usually want to avoid either the substance or the appearance of unfair
treatment of the servers, for whom tips (at least in restaurants in the United
States) are a major component of pay.
In one restaurant, a food server recorded the following data on all cus-
tomers they served during an interval of two and a half months in early 1990.
The restaurant, located in a suburban shopping mall, was part of a national
chain and served a varied menu. In observance of local law, the restaurant
offered to seat in a non-smoking section to patrons who requested it. Each
record includes a day and time, and taken together, they show the server’s
work schedule.

### Recent Grads
The recent grads dataset contains basic earnings and labor force information in a more detailed breakdown, including by sex and by the type of job they got. The maximum age of participants in this dataset is 28.

Headers for `recent-grads.csv` are shown below:

Header | Description
---|---------
`Rank` | Rank by median earnings
`Major_code` | Major code, FO1DP in ACS PUMS
`Major` | Major description
`Major_category` | Category of major from Carnevale et al
`Total` | Total number of people with major
`Sample_size` | Sample size (unweighted) of full-time, year-round ONLY (used for earnings)
`Men` | Male graduates
`Women` | Female graduates
`ShareWomen` | Women as share of total
`Employed` | Number employed (ESR == 1 or 2)
`Full_time` | Employed 35 hours or more
`Part_time` | Employed less than 35 hours
`Full_time_year_round` | Employed at least 50 weeks (WKW == 1) and at least 35 hours (WKHP >= 35)
`Unemployed` | Number unemployed (ESR == 3)
`Unemployment_rate` | Unemployed / (Unemployed + Employed)
`Median` | Median earnings of full-time, year-round workers
`P25th` | 25th percentile of earnigns
`P75th` | 75th percentile of earnings
`College_jobs` | Number with job requiring a college degree
`Non_college_jobs` | Number with job not requiring a college degree
`Low_wage_jobs` | Number in low-wage service jobs

## Learning Objectives
For this week we willl be focusing on the following goals:
- We will use visualization as an analysis tool instead of using Pandas DataFrame 
- Check if the tips recieved by a waiter are dependent on the other factors such as
    - Sex
    - day
    - time
    - size of group
    - smokers or non-smokers
- We will use the learning the following types of plots:
    - Univariate plots
        - Histogram
        - Kerner Density Estimation (KDE)
        - Distplot
    - Bivariate plots
        - Scatterplot
        - Lineplot
        - Jointplot (*Basic, Hex, KDE*)
    - Categorical Datatypes
        - Scatterplot.
        - Boxplot.
        - Violin plot.
- Use Seaborn to make beautiful visualizations and tell a story.


## About the Library
### Seaborn
Seaborn is a library for making statistical graphics in Python. It is built on top of matplotlib and closely integrated with pandas data structures.Here is some of the functionality that seaborn offers:

- A dataset-oriented API for examining relationships between multiple variables
- Specialized support for using categorical variables to show observations or aggregate statistics
- Options for visualizing univariate or bivariate distributions and for comparing them between subsets of data
- Automatic estimation and plotting of linear regression models for different kinds dependent variables
- Convenient views onto the overall structure of complex datasets
- High-level abstractions for structuring multi-plot grids that let you easily build complex visualizations
- Concise control over matplotlib figure styling with several built-in themes
- Tools for choosing color palettes that faithfully reveal patterns in your data
Seaborn aims to make visualization a central part of exploring and understanding data. Its dataset-oriented plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots.

## Resources
- [Recent Grads](http://www.census.gov/programs-surveys/acs/data/pums.html)


