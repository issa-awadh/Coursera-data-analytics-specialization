# Coursera-data-analytics-specialization
# Bike Sharing Data Analysis and Clustering

## Introduction
This project analyzes bike-sharing data to extract insights and understand usage patterns. The dataset consists of four quarters of Divvy bike-sharing data from 2019. The analysis includes data cleaning, transformation, exploratory data analysis (EDA), and K-means clustering to segment trips based on similar characteristics.

## Dataset
The dataset used for this analysis includes:
- `Divvy_Trips_2019_Q1.csv`
- `Divvy_Trips_2019_Q2.csv`
- `Divvy_Trips_2019_Q3.csv`
- `Divvy_Trips_2019_Q4.csv`

## Tasks Performed
1. **Data Importation**
   - Mounted Google Drive to access the dataset.
   - Imported required libraries (Pandas, NumPy, etc.).
   - Loaded quarterly datasets into Pandas DataFrames.

2. **Data Inspection**
   - Displayed the first few rows of each dataset.
   - Identified key columns and data types.
   
3. **Data Cleaning & Transformation**
   - Converted date columns to `datetime` format.
   - Converted `tripduration` to `float64`.
   - Removed null values in the `gender` and `birthyear` columns.
   - Created a `day_of_week` column to represent the day of the week in a user-friendly format.

4. **Exploratory Data Analysis (EDA)**
   - Analyzed trip durations, user types, and ride patterns.
   - Identified trends based on time of day and day of the week.
   - Visualized distributions and correlations between variables.

5. **K-Means Clustering**
   - Selected relevant features for clustering.
   - Scaled features as necessary for improved clustering performance.
   - Applied the K-means clustering algorithm to segment trips/users.
   - Determined the optimal number of clusters using the elbow method.
   - Interpreted the resulting clusters to derive actionable insights.

## Requirements
- Python (Jupyter Notebook)
- Pandas
- NumPy
- Scikit-learn (for K-means clustering)
- Google Colab (optional)

## How to Use
1. Open the Jupyter Notebook in Google Colab or a local environment.
2. Ensure the dataset files are accessible.
3. Run the notebook cells sequentially to clean, analyze, cluster, and visualize the data.

## Summary
This project provides a structured approach to analyzing bike-sharing data. It covers data preprocessing, transformation, exploratory analysis, and clustering to derive meaningful insights from user behaviors and trip patterns.

---
*Author: [Issa Awadh]*


