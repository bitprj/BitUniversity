<p align="center">
<img src="https://github.com/bitprj/BitU-3WBootCamp/blob/Narae/Week%202%20-%20Working%20with%20Data%20using%20Pandas/images/DataManipulationGraphic.jfif" width="640" height="400">
 </p>


# <div align="center"> Working with Data Using Pandas </div>

### Recap

Last week, we covered the basics of Python, including concepts such as: 

- **Numbers**: We discussed how Python supports a variety of number types, basic arithmetic, and other calculations. 
- **Variable Assignment**: We discussed how variables in Python are very similar to to their math equivalents and are used for storing data.
- **Strings**: We discussed how strings are how Python represents English letters, words, and phrases as data as well as the different properties and attributes of strings.
- **Booleans**: We discussed how Booleans are represent True/False and how they are used in evaluating logical conditions or produced as a result of them.
- **Lists**: We discussed how lists are a generic type of sequence and how they can store data of multiple types in one, easy-to-access structure.
- **Tuples**:  We discussed how tuples are almost exactly like lists except that they are immutable - they cannot be modified.
- **Dictionaries**: We discussed how dictionaries can be used when you have two different sets of data that have a one-to-one relationship and want to store both in one structure that preserves this relationship.
- **Comparison Operators**: We discussed how comparison operators are used like they are in math and are then used to create logical conditions.
- **Functions**: We discussed how functions are how programmers store a chunk of code that they know they will reuse multiple times in the future, and how this saves them from coding it again every time they need this code.
- **Modules and Packages**. We discussed how modules are essentially entire python programs that you import into your own so that you can reuse all the code that is present in that file and how packages are larger files that can contain multiple modules or even other packages.

## Learning Objectives

For this week, we will focus on data manipulation using Pandas. Pandas is an open source data analysis tool, built on top of the Python programming language. Since we are now familiar with the basic concepts of Python, you will now be able to understand the syntax and data structures we use in this tutorial.

By the end of the week, you will learn how to do the following with Pandas:

- Import data and create Dataframes
- Gather information about the dataset
- Set a custom index for the dataset
- Select specific data using indexing
- Remove columns, rows, or NaN (None) values from data
- Analyze unique values
- Filter the dataset based on your criteria
- Use aggregation functions such as groupby on the data

Thus, by the end of this week, you will have an excellent foundation for data analysis using Pandas. 

## About the Libraries

### Pandas

[![img](https://github.com/bitprj/DigitalHistory/raw/Narae/Week3-Introduction-to-Open-Data-Importing-Data-and-Basic-Data-Wrangling/assets/icons/pandas.png?raw=1)](https://github.com/bitprj/DigitalHistory/blob/Narae/Week3-Introduction-to-Open-Data-Importing-Data-and-Basic-Data-Wrangling/assets/icons/pandas.png?raw=1)

Pandas stands for **Python Data Analysis Library**. Pandas is an open source data analysis and manipulation tool and it is widely used in both academia and industry.  As explained earlier, Pandas is built on top of the Python programming language and it offers data structures and operations for manipulating numerical tables and time series.

## About the Dataset

### Titanic Dataset

[![img](https://github.com/bitprj/DigitalHistory/raw/Narae/Week3-Introduction-to-Open-Data-Importing-Data-and-Basic-Data-Wrangling/assets/icons/titanic.png?raw=1)](https://github.com/bitprj/DigitalHistory/blob/Narae/Week3-Introduction-to-Open-Data-Importing-Data-and-Basic-Data-Wrangling/assets/icons/titanic.png?raw=1)

To demonstrate how to use Pandas and dataframes (the data structure used in Pandas), we will use a dataset about the Titanic. The Titanic was a British passenger liner operated by the White Star Line that sank in the North Atlantic Ocean in 1912, after striking an iceberg during her maiden voyage from Southampton to New York City. Of the estimated 2,224 passengers and crew aboard, more than 1,500 died. 

Using Pandas, we will calculate the survival rates in different demographics as well as the correlation between the survival rate and other factors such as gender, age, etc. 

## Resources

If you would like to learn more about Pandas or need further help while going through the notebook, here are some resources you can refer to.

[Pandas Dataframe API](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html) - a reference page that details all the different functions and aspects of Pandas

[Pandas Tutorials](https://pandas.pydata.org/pandas-docs/version/0.15/tutorials.html) - a page featuring many different tutorials for both beginners and more experienced users

[Python for Data Analysis Book](https://www.programmer-books.com/wp-content/uploads/2019/04/Python-for-Data-Analysis-2nd-Edition.pdf) - a pdf of the Python for Data Analysis book, detailing not only Pandas but other data analysis tools that use Python, written by the creator of Pandas himself

------

