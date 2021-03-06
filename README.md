# Python Basics For Data Analytics

This repository contains a course on the basics of python programming for a beginner. This repository contains basic datasets to illustrate the core concepts we will be exploring, however, you are free (and should) practice on datasets of your interest in order to find interesting insights.

This course is split up into 5 sections, they are: 

- Core programming principles
- Fundamentals of python
- Matrices
- Data Frames
- Exploring visualisations

We will be using Juypter notebook that comes with the Anaconda Navigator GUI. This can be downloaded by using the following link:

https://docs.anaconda.com/anaconda/navigator/

## Section 1: Core Programming Principles

In this section, we cover:

- Types of variables: 
  - Integers
  - Float 
  - Strings
  - Logical/boolean
  - Using variables
  - Using boolean variables and operators
  
- Loops:
  - While loops
  - For loops
  - If statements
  - Nested loops
  - Chained statements

Normal distribution diagram: https://towardsdatascience.com/understanding-the-68-95-99-7-rule-for-a-normal-distribution-b7b7cbf760c2

## Section 2: Fundamentals of Python

In this section, we cover:

- Lists:
  - What a list is
  - Creating lists: [], range()
  - Using the [] brackets
  - Slicing lists
  - Tuples
  
- Tuples
- Functions
- Packages
- Numpy and Arrays
- Slicing Arrays

### Packages in python

Packages contain different functions that are used to carry out tasks.

**Module:** A module is simply a file containing Python definitions, functions and statements. Putting code into modules is useful because of the ability to import the module functionality into your script or IPython session.

**Package:** A package is just a way of collecting related modules together within a simple tree like hierarchy. Very complex packages like NumPy or SciPy have hundreds of individual modules so putting them into a directory-like structure keeps things organised and avoids name collisions.

Steps: 
- Find the package (optional)
- Install package (pip install package_name)
- Import package_name (e.g. import numpy as np) or Import function (e.g. from sklearn import metrics)

## Section 3: Matrices

In this section, we cover:

- Matrices:
  - Building matrices: ```np.reshape(*, *, 'C'), np.reshape(*, *, 'F), np.array()```
  - Matrix operations
- Dictionaries in python
- Visualisations with pyplot
- Creating functions
- Deriving insights

## Section 4: Data Frames

In this section, we cover:

- Importing data into python
- Data frames via Pandas
- Exploring datasets: head(), tail(), info(), describe()
- Renaming columns
- Subsetting data frames
- Basic operations with data frames
- .at() and .iat ()
- Filtering data frames
- Introduction into Seaborn
- Keyword arguments (kws)

## Section 5: Advanced Visualisations

In this section, we cover:

- Data types in python
- Joint plots
- Histograms
- Stacked Histograms
- KDE plots
- Using the Subplots() function
- Box plots and Violin plots
- Facet grids
- Building dashboards
