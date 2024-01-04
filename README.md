# Exploration And Analysis of Crime Data From Nothern Ireland
The dataset used in the project is obtained from the website [Police.UK](https://www.police.uk/). The dataset consists of multiple CSV files containing information about the criminal activity occurring in the Northern Ireland part of the United Kingdom, from December 2019 to November 2022.

## Description

Authored by Md Wahid Hassan, this Jupyter Notebook is a detailed data analysis project on crime data from Northern Ireland, spanning from December 2019 to November 2022. The data is sourced from [Police.UK](https://police.uk). Developed using Google Colab, the project entails extensive data exploration, analysis, and visualization.

## Initial Setup
- The notebook begins with the installation of essential Python packages and LaTeX tools for PDF conversion.
- Libraries imported include `numpy`, `pandas`, `matplotlib`, `seaborn`, `geopandas`, `folium`, and `sklearn`.
- Google Drive is mounted for accessing the dataset.
- The crime data, encompassing multiple CSV files, is consolidated into a single pandas DataFrame.

## Basic Exploration
- Utilizing pandas functions, the dataset's structure, summary statistics, and crime type frequencies are explored.

## Data Transformation
- Relevant columns are selected, null values are managed, and the 'Month' column is converted to a datetime format. A backup DataFrame is also created.

## Exploratory Data Analysis
- Spatial analysis is conducted using `folium` and `geopandas` for crime density mapping.
- Histograms for 'Latitude' and 'Longitude' are plotted.
- A stacked column chart visualizes the yearly distribution of different crime types.

## Statistical Tests
- Three hypothesis tests are performed:
  1. Chi-square test for independence between crime type and month.
  2. t-test for mean comparison of latitude and longitude.
  3. ANOVA for examining latitude mean differences across crime types.

## Outlier Detection
- Outliers in the data are identified using z-scores and visualized.

## Seasonal Decomposition and Trend Analysis
- `seasonal_decompose` from the time series analysis library is applied to identify seasonal patterns.
- Line charts and pivot tables are used for trend analysis over time and across crime types.

## Forecasting Using FbProphet
- FbProphet tool is utilized for forecasting future crime trends for different crime types.

## Conclusion
- The project concludes with significant findings, including:
  - Identification of redundant columns and data entry issues.
  - Non-normal distribution in latitude and longitude.
  - Statistical evidence supporting alternate hypotheses.
  - Outlier analysis.
  - Crime trends and seasonality insights.
  - Predictive forecasts for future crime trends.

The notebook includes code snippets for PDF report generation, demonstrating a holistic approach to data science, encompassing spatial analysis, statistical testing, time series analysis, and predictive modelling.
