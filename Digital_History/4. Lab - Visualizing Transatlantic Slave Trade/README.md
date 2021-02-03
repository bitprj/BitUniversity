
<div align ="center"> <img src="assets/ship.jpg"> </div>

# <div align="center">Visualizing the Transatlantic Slave Trade</div>

## Practicum Methodology
Congratulations, you have made it to the practicum lab of this course! The focus of this lab is to help you learn and apply a structured approach when working on a project. You will be using the tools such as ```pandas``` and ```matplotlib``` to explore the dataset. 
To do so, we will divide our approach into 4 parts:
- The first part is the traditional setup every data scientist has to do when starting a project. These include loading datasets and observing the basic numerical analysis of the dataset. 
- The second part involves cleaning the dataset and choosing columns that fit our methodology.
- The third part involves further splitting our cleaned dataframe into smaller dataframes and visualizing them.
- Finally, the fourth part involves summarizing our conclusion.

## Recap
- By this point, you should have a general understanding on how to do the following:
- Loading a Dataset '.csv' as a dataframe using ```pd.read_csv```
- Observing the properties of the loaded dataset using functions such as:
    - ```pd.head()```
    - ```pd.describe()```
    - ```pd.info()```
- Modifying the dataset by removing ```NaN``` values.
- Using ```objects``` in DataFrames.
- Re-indexing columns
- Visualizing Data using ```matplotlib``` and ```pandas```:
    - Scatter plots
    - Barplots
    - Line plots
    - Histograms

## About the Dataset

### The Trans-Atlantic Slave Trade

It is difficult and sad to believe that in the first decades of the twenty-first century that just over two centuries, the shipping of enslaved Africans across the Atlantic was morally indistinguishable from shipping textiles, wheat, or even sugar. Our reconstruction of a major part of this migration experience covers an era in which there was a massive technological change (steamers were among the last slave ships), as well as very dramatic shifts in perceptions of good and evil. Just as important to examine is the relationship between the Western and non-Western worlds that the trade both reflected and encapsulated. Slavery constituted the most important reason for contact between Europeans and Africans for nearly two centuries. The shipment of slaves from Africa was in part caused by the demographic disaster due to the meeting of Europeans and Native Americans, which greatly reduced the numbers of Native American laborers and raised the demand for labor drawn from elsewhere, particularly Africa. As Europeans colonized the Americas, a steady stream of European peoples migrated to the Americas between 1492 and the early nineteenth century. But what is often overlooked is that, before 1820, perhaps three times as many enslaved Africans crossed the Atlantic as Europeans. This was the largest transoceanic migration of a people until that day, and it provided the Americas with a crucial labor force for their own economic development. Thus, we must acknowledge the millions of Africans and their descendants who essentially built America, as well as the effects of their journey here. 

The details of the more than 36,000 voyages presented here greatly facilitate the study of cultural, demographic, and economic change in the Atlantic world from the late sixteenth to the mid-nineteenth centuries. Trends and cycles in the flow of African captives from specific coastal outlets should provide scholars with new, basic information useful in examining the relationships among slavery, warfare—in both Africa and Europe—political instability, and climatic and ecological change, among other forces. 

#### Facts about the dataset

- The dataset covers approximately 36,110 trans-Atlantic voyages.
- The estimates suggest around 12,520,000 captives departed Africa to the Americas. 

- Not all 36,000 voyages in the database carried slaves from Africa.
- A total of 633 voyages (1.8%) never reached the African coast because they were lost at sea, captured, or suffered some other misfortune. 
- The database also contains records of 34,106 voyages that disembarked slaves or could have done so (in other words, for some of these we do not know the outcome of the voyage).
- The latter group comprised mainly ships captured in the nineteenth century which were taken to Sierra Leone and St. Helena as part of the attempt to suppress the trade. 

## Learning Objectives

## About the Libraries
The libraries we will be using for this Lab are:

### Pandas
Pandas is an open-source, BSD-licensed Python library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language. Python with Pandas is used in a wide range of fields including academic and commercial domains including finance, economics, statistics, analytics, etc. In this tutorial, we will learn the various features of Python Pandas and how to use them in practice.

### Matplotlib
The matplotlib Python library, developed by John Hunter and many other contributors, is used to create high-quality graphs, charts, and figures. The library is extensive and capable of changing very minute details of a figure. Some basic concepts and functions provided in matplotlib are:

matplotlib.pyplot is a collection of functions that make matplotlib work like MATLAB. Each pyplot function makes some change to a figure: e.g., creates a figure, creates a plotting area in a figure, plots some lines in a plotting area, decorates the plot with labels, etc.

In matplotlib.pyplot various states are preserved across function calls so that it keeps track of things like the current figure and plotting area, and the plotting functions are directed to the current axes (please note that "axes" here and in most places in the documentation refers to the axes part of a figure and not the strict mathematical term for more than one axis).




## Resources

- [Brookes](https://en.wikipedia.org/wiki/Brookes_(ship))
- [Transatlantic Slave Trade](https://www.britannica.com/topic/transatlantic-slave-trade)
- [Slave Voyages](https://www.slavevoyages.org/)
- [Matplotlib](https://matplotlib.org/3.3.1/tutorials/index.html)
- [Pandas Dataframes](https://pandas.pydata.org/docs/reference/frame.html)


