# NumPy Student Score Dataset Analysis

A beginner-friendly project focused on mastering the core concepts of NumPy through practical exercises using a student scores dataset.

This repository contains solutions to commonly used NumPy operations such as array creation, indexing, slicing, aggregation, statistical analysis, sorting, flattening, conditional filtering, and data manipulation.


## Project Overview

NumPy is the foundation of the Python data science ecosystem. Before moving to libraries such as Pandas, Scikit-Learn, and TensorFlow, it is important to develop a strong understanding of NumPy arrays and operations.

This project was created to practice and reinforce the most frequently used NumPy concepts through a structured set of dataset-based questions.

## Dataset

The dataset consists of student scores across three subjects.

## python

import numpy as np

scores = np.array([
    [85, 90, 78],
    [88, 76, 92],
    [90, 89, 85],
    [70, 80, 75],
    [95, 92, 98]
])

### Dataset Structure

| Student | Subject 1 | Subject 2 | Subject 3 |
|----------|----------|----------|----------|
| Student 1 | 85 | 90 | 78 |
| Student 2 | 88 | 76 | 92 |
| Student 3 | 90 | 89 | 85 |
| Student 4 | 70 | 80 | 75 |
| Student 5 | 95 | 92 | 98 |

---

## Topics Covered

### Array Properties
- Shape of an array
- Total number of elements
- Dimensionality

### Indexing & Slicing
- Accessing individual elements
- Extracting rows
- Extracting columns

### Statistical Operations
- Mean
- Minimum value
- Maximum value
- Standard deviation

### Aggregation
- Sum of rows
- Sum of columns
- Average marks per student
- Average marks per subject

### Data Manipulation
- Adding grace marks
- Replacing values using conditions
- Sorting values
- Flattening arrays

### Boolean Indexing
- Creating boolean masks
- Filtering data using conditions
- Counting matching values

### Advanced NumPy Functions
- `np.where()`
- `np.argmax()`
- Boolean masking
- Broadcasting
- 

## Exercise List

### Basic Exercises

1. Find the shape of the dataset.
2. Find the total number of elements.
3. Extract marks of the first student.
4. Extract marks of the third subject for all students.
5. Find the average marks of each student.
6. Find the average marks of each subject.
7. Find the highest mark in the dataset.
8. Find the lowest mark in the dataset.
9. Find students whose average score is greater than 85.
10. Add 5 grace marks to every score.
11. Replace all scores below 80 with 80.
12. Find the standard deviation for each subject.
13. Sort the marks of the second student.
14. Flatten the dataset into a one-dimensional array.
15. Count scores greater than 90.

### Additional Practice

16. Find the index of the highest score.
17. Calculate the sum of marks for each student.
18. Calculate the sum of marks for each subject.
19. Create a boolean mask for scores greater than or equal to 90.
20. Extract all scores greater than or equal to 90 using the mask.

---

## Skills Practiced

By completing this project, you will gain hands-on experience with:

- NumPy Arrays
- Array Indexing
- Array Slicing
- Statistical Computations
- Aggregation Functions
- Boolean Masking
- Conditional Selection
- Data Cleaning Techniques
- Broadcasting
- Array Transformations
- 

## Technologies Used

- Python 3
- NumPy


## Learning Outcome

After completing these exercises, you should be able to:

- Work confidently with NumPy arrays
- Perform data analysis using vectorized operations
- Filter and manipulate data efficiently
- Apply statistical calculations on datasets
- Understand the fundamentals required for learning Pandas and Data Science workflows



## Future Improvements

Planned extensions for this repository:

- Pandas Fundamentals Exercises
- Data Cleaning Challenges
- Real-World CSV Dataset Analysis
- Data Visualization with Matplotlib
- Mini Data Analysis Projects


## Author: Dhruv Ameta
