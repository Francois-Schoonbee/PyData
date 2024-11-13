# Session 6 code

## Overview
In this session we learned how to use the Pandas package to load and explore data, clean data and do preprocessing with Pandas.

## Required packages (with code to install if neccesary)
- Pandas (pip install pandas)
- Numpy (pip install numpy)

## Datasets
Make sure to download the netflix_titles and train_and_test2 csv files and that they are in the correct working directory fot eh code to work properly.

## Introduction Code

### Pandas function
The code starts by giving short examples of different pandas functions, including loc(), iloc(), tail(), head(), at() and more. 
### Filtering
Then some examples are given on how to filter datasets to extract only certain entries. This could be entries in the datset for which one column is larger that 25 for example.

### Missing values
Some examples are given on how to identify, replace and handle missing values in datasets.

### Groupby

groupby() is a very useful function in the Pandas package that can be use to calculate a variety of statistics for datsets. These are some statistics that can be calculated:
- count
- mean
- sum
- min and max
- multiple aggregations
- group using multiple columns

This is followed by some examples

## Netflix code

In this part the netflix csv file is loaded and used to illustrate the capabilities of the Pandas package. This is a list of all the excercises done:
### Class exercises
1. Count Missing Values in Each Column
2. Fill Missing 'country' Values with "Unknown"
3. Filter for TV Shows Only
4. Count the Number of Entries per Rating
5. Add a Column Showing Content Age (how many years since it came out)
### Home exercises:
1. Is there any missing rating?
2. How many films in 2021 correspond to your country? (South Africa)
3. What's the number of movies in 2020 with full information?
4. Identify the year with the most titels
5. And what has been the average in terms of releases from 2010.

## Titianic dataset

Next the Titanic dataset (train_and_test2.csv) is loaded and used. This is a list of all the exercises done:

### Class exercises

1. Count the Missing Values in Each Column
2. Fill Missing 'Age' Values with the Mean Age
3. Fill Missing 'Embarked' Values with the Mode (Most Common Value)
4. Filter and Display Passengers Who Paid a Fare Above the Average Fare
5. Add a New Column Indicating Family Size. Create a new column 'FamilySize' as the sum of 'SibSp' (siblings/spouses) and 'Parch' (parents/children)

### Home exercises

1. Calculate Gender-Based Survival Percentage
2. Calculate Survival Percentage Grouped by Gender and Class
