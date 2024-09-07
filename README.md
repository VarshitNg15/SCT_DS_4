# US Accidents Analysis

This project focuses on analyzing the dataset `US_Accidents_March23.csv`, which contains detailed information about accidents across the United States. The analysis aims to uncover patterns and insights related to weather conditions, time of day, geographical hotspots, and other variables that affect accident occurrences.

## Project Overview

The primary objective of this project is to:

1. Clean and preprocess the dataset.
2. Visualize accident distributions based on weather conditions, temperature, wind speed, and time of day.
3. Identify accident hotspots geographically.
4. Perform correlation analysis to understand the relationships between key variables (temperature, wind speed, visibility, etc.).
5. Conduct a Chi-square test to determine if weather conditions significantly affect accident severity.

## Analysis Workflow

1. **Data Loading**: The dataset is loaded using `pandas` for analysis.
2. **Data Cleaning**: Missing values in important columns like `Weather_Condition`, `Start_Time`, `Start_Lat`, and `Start_Lng` are dropped.
3. **Data Transformation**: The `Start_Time` column is converted to datetime format, and additional time-based features like `Hour` are extracted.
4. **Visualizations**: 
    - Accident distribution by weather conditions.
    - Accident distribution by temperature and wind speed.
    - Hourly distribution of accidents.
    - Geographical hotspots based on accident locations.
5. **Correlation Analysis**: A correlation matrix is computed for variables such as temperature, wind speed, and visibility.
6. **Chi-square Test**: A chi-square test is performed to assess the relationship between weather conditions and accident severity.

## Key Visualizations

- **Weather Condition Distribution**: Bar plot showing the frequency of accidents under different weather conditions.
- **Temperature & Wind Speed Distribution**: Histogram plots with kernel density estimation for temperature and wind speed at accident times.
- **Hourly Distribution**: Count plot showing how accidents vary by the hour of the day.
- **Accident Hotspots**: Scatter plot visualizing the geographic locations of accidents to highlight hotspots.
- **Correlation Matrix**: A heatmap illustrating the correlations between variables like temperature, wind speed, precipitation, and visibility.

## Statistical Test

A chi-square test was conducted to examine the relationship between weather conditions and accident severity. The results showed the following:

- **Chi-square statistic**: `X.XX`
- **p-value**: `X.XX`

The low p-value indicates that there is a statistically significant relationship between weather conditions and the severity of accidents.


## Conclusion

The analysis highlights significant patterns in accident occurrence based on weather conditions, temperature, and time of day. The findings also reveal accident hotspots across the country, and statistical analysis confirms that weather conditions significantly affect accident severity.
