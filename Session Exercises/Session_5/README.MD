# Session 5 

## Overview
In this session we covered using diffrent formats (json, pickle, and parquet), the Re library and the Time and Datetime libraries

## Introductory code
In the beginning some basic fucntionalisties are illustrated. These functionalisties are useful for creating and manipulating files. These examples include:
- Opening, writing and closing text files
- Creating csv files
- Examples of the JSON format
- Reading and writing JSON files
- Reading and writing Pickle files
- Reading and writing Pacquet files

### Regex package
The regex package (re), is very useful to perform complex pattern matching using wildcards and other special characters. The fictionality is the illusrated by loading the session_4 folder and doing pattern matching. 

### Time and Datetime package
The Time and DateTime package is very useful for time measurements, timestamps and date manupulation. Their functionalities are then illustrated by doing the following:
- Getting the current timestamp
- Waiting a certain amount of time
- Changing the format of dates
- Ordering and printing the annotation by date 

## Exercises
Using the session_4 folder perform the following exercises:
1. How many annotations you have per month and year. Which month has more annotation files.
2. Create a dictionary where each **key** is a month, and the corresponding **value** is a list containing all the annotation names with where their date corresponds to the month. 
    a. Save it following the json format, and load it again to check that everything is ok.
    b. Save it this time using Pickle.
    c. Instead of storing a list of all the annotation names happening that month, let's create for each annotation a dictionary with keys: name and date (using a datetime object).
3. Print all the annotations from the oldest ones to the newest one during the seconf half of the 2024. 

## Requirements
To complete this session, **download the `session_4.zip` file**, which includes all the necessary data annotations. Extract the zip file in the same directory as the notebook to ensure that all data files load without issues.

### Libraries Needed
- **pandas**
- **NumPy**
- **scikit-learn**
- **matplotlib**

If you need to install any missing libraries, use:
```bash
pip install pandas numpy scikit-learn matplotlib
