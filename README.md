# OIBSIP Data Science Task 2 – Unemployment Analysis in India

## Objective
This project focuses on analyzing the unemployment rate in India during and after the COVID-19 pandemic using real-world data. The aim is to understand regional disparities, temporal trends, and the overall economic impact through data visualization and exploratory analysis.

## Dataset Details

The dataset contains monthly unemployment statistics for various Indian states and includes the following fields:

| Column                               | Description                              |
|--------------------------------------|------------------------------------------|
| Region                               | State or Union Territory in India        |
| Date                                 | Month and year of the observation        |
| Estimated Unemployment Rate (%)      | Percentage of unemployed individuals     |
| Estimated Employed                   | Total estimated employed individuals     |
| Estimated Labour Participation Rate (%) | Participation rate in the labor force  |
| Area                                 | Indicates whether the data is for Rural or Urban areas |

Dataset used: `Unemployment_Rate_upto_11_2020.csv`

## Steps Performed

### 1. Data Loading
- Loaded the CSV file using pandas.
- Performed an initial data inspection and summary.

### 2. Data Cleaning and Formatting
- Converted date column to datetime format.
- Renamed columns for clarity and consistency.
- Handled missing or inconsistent values if any.

### 3. Exploratory Data Analysis (EDA)
- Calculated average unemployment rates.
- Analyzed trends across states, time periods, and area types.

### 4. Data Visualization
- Created time-series plots for trend analysis.
- Generated heatmaps to show month-wise changes.
- Created bar charts for comparing regional unemployment.
- Built interactive choropleth maps using Plotly to visualize state-wise unemployment rates.

## Tools and Libraries Used

- Python
- pandas, numpy
- matplotlib, seaborn
- plotly
- Jupyter Notebook

## Key Insights

- Unemployment surged significantly in April and May 2020 across most regions.
- States like Haryana, Jharkhand, and Bihar experienced some of the highest unemployment rates.
- Rural areas showed a faster recovery in employment compared to urban areas post-lockdown.
- Labor participation rates fluctuated sharply during the lockdown period, indicating instability in job security.

