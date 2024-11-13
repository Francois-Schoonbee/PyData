# Session 4 - Python for Data Science

## Overview
This notebook focuses on **Data Annotation and Preprocessing**. The objective of this session is to guide you through loading, annotating, and preprocessing data to prepare it for further analysis or model training. We also cover key Python libraries like **pandas**, **NumPy**, and **matplotlib** for handling and visualizing datasets.

## Code

### Basic Libraries

In this part some basic libraries are loaded and some examples of the functionality of the usefullness of these libraries are given. These include some of the following:

### Numpy
- Create an array
- Indexing
- Array calculations
- Ordering an array
- Randomisation
- Combining and shaping arrays

### Scipy
- Solving multiple equation using linalg
- Integration
- t-test

### Basic built in packages
In this part basic package math, os and glob are used. The following examples are given
- Basic math function suxh as exp(), log(), pow()
- Creating and removing files
- Extracting file names
- Listing files
- Copying and moving files
- Creating and deleting files

## Exercises

In the exercise portion the folder session_4 is loaded and used to perform different fucntions with the libraries. These exercises include:
Given a zip file with a subfolder with multiple annotations, where the name convention for each one of them is: 

{DATE}_{TIME}_SN{SATELLITE_NUMBER}_QUICKVIEW_VISUAL_{VERSION}_{UNIQUE_REGION}.txt

where:

- DATE expressed as YYYYMMDD (year, month and day), e.g. 20241201, 20230321 ...
- TIME expressed as HHMMSS (hour, minutes and seconds), e.g. 2134307
- SATELLITE_NUMBER an integer that represents the satellite number.
- VERSION provides the version of the pipeline, e.g. "0_1_2", "1_3_1" ...
- UNIQUE_REGION provides a unique location in the form of a string, e.g SATL-2KM-10N_552_4164

Find out the following thing about your data:

1. How many files the annotations folder has.
2. How many of them follow the name convention expressed above.
3. How many of annotations you have per month and year. Which month has more annotation files.
4. Create a new annotations folder with multiple folders corresponding to a month.
5. Print all the annotations from the most recent to the oldest one. 
6. How many different satellites there are, how many annotations we have per satellite number, and which one was used in the most recent annotation file. 
7. How many unique regions there are.

## Requirements
Before running the notebook, make sure to download the **session_4.zip** file containing the annotations needed for the exercises. Unzip it into the same directory as the notebook so that all the data files load correctly.

### Libraries Needed
- **pandas**
- **NumPy**
- **matplotlib**

To install any missing libraries, use:
```bash
pip install pandas numpy matplotlib

