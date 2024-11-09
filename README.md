# Amazon Sales Report Analysis

This project involves exploratory data analysis (EDA) on an Amazon sales dataset to uncover insights into customer preferences,product performance, and geographical sales distribution.
The analysis includes data cleaning, transformation, and visualizations to support business decisions.

# Table of Contents

  1. Project Overview
  2. Features
  3. Technologies Used
  4. Data Preprocessing
  5. Data Analysis and Visualization
  6. Snapshots
  7. Conclusion

# Project Overview

The Amazon Sales Report Analysis project uses a dataset containing information on Amazon product sales, including quantities sold, order status, customer location, and more. 
The goal is to analyze this data to identify key trends, such as top-selling product sizes, preferred states for sales, and the demand for various product categories.

# Features

* Data Cleaning: Handled missing values and irrelevant columns.
* Data Transformation: Converted columns to appropriate data types, renamed columns, and created visual summaries.
* Statistical Summary: Provided a descriptive summary of numeric and categorical columns.
* Visual Analysis: Produced bar plots, pie charts, histograms, and scatter plots to represent data visually.

# Technologies Used

  ## Python Libraries:
     * pandas: For data loading, manipulation, and summarization
     * numpy: For numerical operations
     * matplotlib and seaborn: For creating visualizations
     * datetime: For handling date data
     
# Data Preprocessing
The preprocessing steps included:

  * Loading Data: Imported the dataset from a CSV file.
  * Shape and Initial Exploration: Checked the shape and a few initial rows of data.
  * Handling Missing Values: Dropped blank columns and rows with missing values.
  * Data Type Conversion: Converted ship-postal-code to integer and Date to datetime.
  * Renaming Columns: Renamed columns for readability (Qty to Quantity and currency to Currency).

# Data Analysis and Visualization
Several insights were obtained from the data through visualization techniques:

  * Category Demand: The distribution of product categories was analyzed using a histogram.

    ![Category ](https://github.com/user-attachments/assets/b37a7088-c2c6-414f-8c53-948af41c652f)
    
  * B2B Data: Used a pie chart to show the percentage distribution of B2B and non-B2B transactions.

    ![B2B](https://github.com/user-attachments/assets/c35ec3f0-70c4-46b1-9062-95d1aacf40b8)
    
  * State Distribution: Visualized the distribution of sales across states with a bar chart.
  * Top 10 States: A bar chart highlighting the states with the highest sales.
  * Product Size Demand: Displayed quantity sold by product size.

    ![Amazon](https://github.com/user-attachments/assets/eb3a74ad-11c7-454b-942b-91b2584d0347)
    
  * Scatter Plot Analysis: Analyzed the relationship between Category and Size using a scatter plot.
    
# Conclusion
The analysis provided valuable insights:

* Geographical Focus: The majority of the customer base is located in Maharashtra.
* Customer Type: The business primarily serves retailers and fulfills orders through Amazon.
* Product Demand: T-shirts are in high demand, with the M-size being the most popular among buyers.
