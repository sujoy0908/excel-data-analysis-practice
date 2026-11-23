# Excel Data Analysis Practice

This repository contains my Excel practice work for data structure and data cleaning.

## Important note
These files are recreated practice files. I did not save my original practice files, so I made them again for this project. The Lesson 1 data is new example data, not the original data.

## Files
- `lesson1_six_orders_recreated.xlsx` - a table of six orders with Order ID, Product and Units.
- `lesson2_sales_cleaning_recreated.xlsx` - a sales column with ₹ symbols, and a cleaned column.

## Lesson 1: Data Structure
**What I did**
- I made a table with 6 orders. It has three columns: Order ID, Product and Units.
- I used the SUM formula on the Units column (C2:C7).

**What I found**
- The total units in this file is 2900.

## Lesson 2: Data Cleaning
**What I did**
- The sales column had some values with the ₹ symbol. Excel read these values as text.
- I used Flash Fill (Ctrl + E) to clean the values into a new column.
- I used COUNT, COUNTA and SUM to check the original column, and COUNT and SUM to check the cleaned column.

**What I found**
- Before cleaning: COUNT = 3, SUM = 600
- After cleaning: COUNT = 5, SUM = 1350
- The numbers were different because Excel does not count text as numbers. The two values with the ₹ symbol (₹300 and ₹450) were text, so COUNT and SUM skipped them.
