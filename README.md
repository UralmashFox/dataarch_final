# The final work for Data Architecture crash course 2022.

## Structure

The repository contains three folders:
- *src*, in which *data* folder contains the source of data (dataset) and *log_parser* folder contains **.ipynb** file with solution;
- *images*, that stores image of table with structured data;
- *presentation* with final work presentation.

## Solution

The solution pipeline is following:

1. to open and read dataset;
2. to parse data into dict ('json' looking) type with fields listed in task:
3. to make visualisation.

## Table

The final table looks like follows:

![table](imges/Diagram.jpg)

and obtains the following fields:

- key;
- device name;
- user number;
- device activity;
- browser statistics;
- response 200 statistics;
- other responses' types statistics;

the type for all fields is **string**.

## Stack

The stack for current work is based on Python 3.10 libraries such as numpy
for statistics calculations, pandas for dataframe operating and 
matplotlib for visualization. I used *jupyter notebook* format in order to
simplify the visualization of the data.


