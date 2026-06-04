# Exploratory Data Analysis (EDA) Project

## Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a student performance dataset to discover patterns, trends, and relationships among different variables. EDA is a crucial step in the data science workflow that helps understand the dataset before applying machine learning models.

## Objective

The objectives of this project are:

* Understand the structure and characteristics of the dataset
* Perform statistical analysis of the data
* Identify patterns and trends
* Discover correlations among variables
* Visualize data using charts and graphs
* Generate meaningful insights from the dataset

## Dataset Description

The dataset contains information about students, including:

* Student ID
* Study Hours
* Attendance Percentage
* Assignments Completed
* Previous Marks
* Result (Pass/Fail)

The dataset is used to analyze factors that influence student performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Exploratory Data Analysis Workflow

### 1. Data Collection

* Loaded the dataset using Pandas
* Verified dataset structure

### 2. Data Inspection

* Examined dataset dimensions
* Identified column names and data types
* Reviewed dataset information

### 3. Statistical Analysis

Generated statistical summaries including:

* Mean
* Median
* Minimum Value
* Maximum Value
* Standard Deviation
* Quartiles

### 4. Data Quality Checks

* Checked for missing values
* Verified duplicate records
* Detected potential outliers

### 5. Data Visualization

Created multiple visualizations to better understand the dataset.

## Visualizations Performed

### Histogram

Used to analyze the distribution of:

* Study Hours
* Attendance
* Previous Marks

### Bar Chart

Used to compare:

* Pass vs Fail distribution
* Average marks by result category

### Box Plot

Used for:

* Outlier detection
* Understanding data spread

### Scatter Plot

Used to analyze relationships between:

* Study Hours and Previous Marks
* Attendance and Previous Marks

### Correlation Heatmap

Used to identify:

* Strong positive correlations
* Strong negative correlations
* Influencing factors affecting student performance

### Pair Plot

Used to visualize relationships among all numerical features simultaneously.

## Key Findings

### Finding 1

Students with higher study hours generally achieve better academic performance.

### Finding 2

Attendance shows a positive relationship with previous marks.

### Finding 3

Students who completed more assignments were more likely to pass.

### Finding 4

Previous marks are one of the strongest indicators of final performance.

### Finding 5

Correlation analysis revealed strong relationships among study habits, attendance, and academic success.

## Statistical Summary

The dataset was analyzed using descriptive statistics to understand central tendency and variability.

Key metrics evaluated:

* Mean
* Standard Deviation
* Variance
* Quartiles
* Range

## Project Structure

EDA-Project/

├── dataset/

│ └── student_data.csv

├── notebook/

│ └── EDA_Project.ipynb

├── output/

│ ├── histogram.png

│ ├── scatter_plot.png

│ ├── boxplot.png

│ ├── heatmap.png

│ └── pairplot.png

├── README.md

└── requirements.txt

## How to Run

### Install Required Libraries

pip install pandas numpy matplotlib seaborn

### Launch Jupyter Notebook

jupyter notebook

### Execute Notebook

Run all notebook cells sequentially.

## Results

The analysis successfully identified:

* Data distribution patterns
* Relationships among variables
* Important factors affecting student outcomes
* Potential trends useful for future predictive modeling

## Conclusion

This Exploratory Data Analysis project provided valuable insights into student performance data. Through statistical summaries and visualizations, important relationships between study habits, attendance, assignments, and academic outcomes were identified. The findings can be used as a foundation for future machine learning and predictive analytics projects.

## Future Scope

* Analyze larger real-world educational datasets
* Perform advanced statistical testing
* Apply clustering techniques
* Integrate predictive modeling for performance forecasting
