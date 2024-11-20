# Session 7 code

## Overview
In this session we learn more about the pandas package. We practiced using lambdas and map functions, data manipulation, handling missing data and data transformation

## Required packages (with code to install if neccesary)
- Pandas (pip install pandas)
- Numpy (pip install numpy)
- Time

## Explanatory Code

### Lambda function and map

We start off by learning how to use lambda and map functions. These can be use to apply any fucntion to a datafram or series

### Advanced data manipulation

We then learn to manipulate data.
We learn how to handle duplicates in many different ways (drop, dropping based on certain columns, deciding which to drop and handling errors)

## Data manipulation excersises

To practice data manipulation we use the Iris dataset and we do the following excersises:
- Series
    - Create a **lambda** function that classifies flowers based on their petal length (e.g., "short" for petal lengths less than 3 cm and "long" for others). Apply this function to the PetalLengthCm column using **apply**.
    - Use **map** to convert the *Species* column into numeric values, e.g. 0 for *Iris-setosa*, 1 for *Iris-versicolor*, 2 for *Iris-virginica*.
- DataFrame
    - Use **value_counts** on the *Species* column to count how many entries belong to each species.
    - Use **drop_duplicates** to remove any duplicate rows from the dataset based on SepalLengthCm and PetalLengthCm.
    - Use **astype** to convert the *SepalLengthCm* column to a string type, then back to float type (if there are any errors, handle them gracefully).
    - Save the modified DataFrame to a CSV file ensuring the index is included (use **to_csv**).

## Explanatory code (continued)

### Advanced data manipulation (continued)
In this part of the code we learn some more data manipulation functions

- How to use pivot_tables and queary function to perform more data manipulation. 
- Learn to join and merge different datasets.
- Setting up, accessing, and slicing multi-level indices
- Handling missing data and data transformation
- String manipulations

## Excersises (part 2)

In these exercises we were given data about professors and did the following:
1. Create a new column called **professor_initials** that stores the initials of each professor's first and last names.
2. Given the dataframe below. Use **join** to combine this new DataFrame with the original one based on the professor column.
3. Combine the original df and df_courses DataFrames.
4. In the professor column, create a new column professor_last_name by extracting the last name of each professor using string operations.

