
<img align="center" src="https://github.com/bitprj/DigitalHistory/blob/master/Week3-Introduction-to-Open-Data-Importing-Data-and-Basic-Data-Wrangling/assets/data-manipulation-cover.png">

# <div align="center">Introduction to Data Manipulation with Pandas </div>

## Recap
Last week, we covered the following concepts in Python:
- **Numbers**. We discussed how Python supports a variety of number types and basic arithmetic and calculations.
- **Variable Assignment**. We discussed how variables in Python are very similar to to their math equivalents and are used for storing data.
- **Strings**. We discussed how strings are how we represent English letters, words, and phrases as data in Python as well as the different properties and attributes of strings.
- **Booleans**. We discussed how Booleans are essentially binary True/False values and that they are primarily used in evaluating logical conditions or produced as a result of them.
- **Lists**. We discussed how lists are a generic type of sequence and how they can store data of multiple types in one, easy-to-access structure.
- **Tuples**. We discussed how tuples are almost exactly like lists except that thay are immutable - they cannot be modified.
- **Dictionaries**. We discussed how dictionaries can be used when you have two different sets of data that have a one-to-one relationship and want to store both in one structure that preserves this relationship.
- **Comparison Operators**. We discussed how comparison operators are exactly the same as in math and are used to create logical conditions.
- **Functions**. We discussed how functions are how programmers store a chunk of code that they know they will reuse multiple times in the future, and how this saves them from reinventing the wheel every time they need this code.
- **Errors and Exception Handling**. We discussed how exceptions are different than errors in that they are hiccups that occur while Python attempts to execute commands, and how handling them effectively is key to preventing your program from halting completely every time a minor setback occurs.
- **Modules and Packages**. We discussed how modules and packages are equivalent to files and folders, respectively. Specifically, we mentioned how modules are essentially entire python programs that you import into your own so that you can reuse all the code that is present in that file, whereas packages can contain multiple modules or even other packages.

## Learning Objectives
For this week, we will focus on the data manipulation using Pandas. Pandas is an open source data analysis and manipulation tool, built on top of the Python programming. Since we are familiar with the basic concepts in Python, it should be easier to understand the syntax and data structures we use in this tutorial. 

By the end of the week, you wil be able to implement the following functions in Pandas Dataframe:

- Importing data
- Setting an index
- Getting info about the dataset
- Removing NaN (None) values
- Selecting subsets of data
- Filtering dataset based on criteria
- Aggregation functions

## About the Libraries
### Pandas

<img src="https://github.com/bitprj/DigitalHistory/blob/Narae/Week3-Introduction-to-Open-Data-Importing-Data-and-Basic-Data-Wrangling/assets/icons/pandas.png?raw=1" width="200" align="center"> 

Pandas stands for **Python Data Analysis Library**. Pandas is an open source data analysis and manipulation tool and it is widely used both in academia and industry. It is built on top of the Python programming language and it offers data structures and operations for manipulating numerical tables and time series.


## About the Dataset 
### Titanic Dataset

<img src="https://github.com/bitprj/DigitalHistory/blob/Narae/Week3-Introduction-to-Open-Data-Importing-Data-and-Basic-Data-Wrangling/assets/icons/titanic.png?raw=1" width="300" align="center"> 

To begin with Pandas and dataframes, we will use a dataset about the Titanic. Titanic was a British passenger liner operated by the White Star Line that sank in the North Atlantic Ocean in 1912, after striking an iceberg during her maiden voyage from Southampton to New York City. Of the estimated 2,224 passengers and crew aboard, more than 1,500 died.

Using Pandas data manipulation, we will figure out the survival rates by different groups and the correlation between the survival rate and another column in the dataset.



## For further assistance

If you would like to learn more about Pandas dataframe, here's the resource you can refer to. Pandas Dataframe API is a library where all of the functions and properties in Pandas are available.

[Pandas Dataframe API](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)
