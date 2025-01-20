# Statistical Data Analysis of Walmart Weekly Sales Data

This project focuses on performing statistical data analysis on Walmart's weekly sales dataset to uncover insights that can help improve business strategies and operational efficiency.

## Project Overview

This project involves analyzing Walmart's weekly sales data to identify trends, seasonal patterns, and relationships between various factors such as store, department, and promotions. The goal is to use statistical methods to draw meaningful conclusions that can aid in business decision-making.

## Dataset Description

The dataset includes the following features:

- **Date**: The week of the sales data.
- **Store**: Unique identifier for each store.
- **Dept**: Department number within the store.
- **Weekly_Sales**: Total sales for the week.
- **Holiday_Flag**: Indicator of whether the week includes a holiday (1 = holiday, 0 = no holiday).
- **Temperature**: Average temperature for the week in Fahrenheit.
- **Fuel_Price**: Price of fuel during the week.
- **CPI**: Consumer Price Index for the week.
- **Unemployment**: Unemployment rate for the week.
- **Size**: Store size in square feet.

## Analysis Steps

1. **Data Cleaning**: Preprocessing of data to handle missing values, outliers, and duplicates.
2. **Exploratory Data Analysis (EDA)**: Visualizing the distribution of key variables and identifying trends over time.
3. **Seasonality and Trends**: Analyzing the data for weekly, monthly, and yearly trends, as well as the impact of holidays on sales.
4. **Correlation Analysis**: Identifying relationships between different variables such as temperature, fuel price, and weekly sales.
5. **Statistical Inference**: Conducting hypothesis testing to assess the significance of various factors on sales.

## Statistical Techniques Used

- **Descriptive Statistics**: Measures such as mean, median, mode, standard deviation to summarize the dataset.
- **Correlation Analysis**: Pearson correlation coefficient to measure the strength of relationships between variables.
- **Time Series Analysis**: Decomposing the time series data to understand trends, seasonality, and noise.
- **Hypothesis Testing**: T-tests and ANOVA to test the impact of holidays, store size, and other factors on sales.
- **Regression Analysis**: Multiple linear regression to predict weekly sales based on different predictors.

## Results

- **Key Findings**: Summarize the insights discovered during the analysis, such as the impact of temperature on sales, holiday effects, and trends over time.
- **Visualizations**: Include graphs such as line plots, bar charts, heatmaps, etc., to showcase the analysis results.

## Technologies and Tools

- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Statsmodels
- Jupyter Notebooks for interactive analysis
- Git for version control

## How to Run the Analysis

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/walmart-weekly-sales-analysis.git
