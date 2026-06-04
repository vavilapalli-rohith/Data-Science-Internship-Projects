# Data Cleaning and Visualization Project

## Overview

This project focuses on cleaning, preprocessing, and visualizing raw customer sales data using Python. The objective is to transform unstructured data into meaningful insights by handling missing values, removing duplicates, detecting outliers, and creating visual reports.

## Objective

The main objectives of this project are:

* Handle missing values in the dataset
* Remove duplicate records
* Detect and treat outliers
* Perform exploratory analysis
* Generate visualizations to identify patterns and trends
* Present key insights from the data

## Dataset Description

The dataset contains customer information including:

* Customer ID
* Age
* Gender
* City
* Monthly Spend
* Number of Orders
* Customer Rating

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Data Cleaning Process

### 1. Missing Value Treatment

* Identified null values using Pandas
* Replaced missing numerical values using appropriate statistical methods

### 2. Duplicate Removal

* Detected duplicate rows
* Removed redundant records from the dataset

### 3. Outlier Detection

* Used the IQR (Interquartile Range) method
* Removed extreme values affecting data quality

### 4. Data Validation

* Verified data types
* Checked dataset consistency after cleaning

## Visualizations Created

### Histogram

Used to understand the distribution of:

* Age
* Monthly Spend
* Orders
* Ratings

### Bar Charts

Used to analyze:

* Customer count by Gender
* Customer count by City
* Average spending by City

### Pie Chart

Used to visualize:

* Gender distribution

### Box Plot

Used to detect:

* Outliers in Monthly Spend

### Scatter Plot

Used to analyze:

* Relationship between Orders and Monthly Spend

### Correlation Heatmap

Used to identify:

* Relationships between numerical variables

### Dashboard

Created a combined dashboard containing multiple visualizations for quick analysis.

## Key Findings

* Customers with higher order counts generally spend more.
* Monthly spending varies significantly across cities.
* The dataset contained missing values and duplicate records which were successfully handled.
* Outliers were identified and removed using the IQR method.
* Correlation analysis revealed relationships among spending, orders, and ratings.

## Project Structure

Data-Cleaning-Visualization/

├── dataset/

│ └── customer_sales_data.csv

├── notebook/

│ └── Data_Cleaning_Visualization.ipynb

├── README.md


## How to Run

1. Clone the repository
2. Install required libraries

pip install pandas numpy matplotlib seaborn

3. Open Jupyter Notebook

jupyter notebook

4. Run all cells in the notebook

## Conclusion

This project demonstrates the complete workflow of data cleaning and visualization. Through preprocessing and visual analytics, meaningful insights were extracted from raw customer sales data, improving data quality and supporting data-driven decision-making.
