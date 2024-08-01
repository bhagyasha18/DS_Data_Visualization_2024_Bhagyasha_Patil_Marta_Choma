# DS_Data_Visualization_2024_Bhagyasha_Patil_Marta_Choma

Global Temperature Analysis
This repository contains the analysis and visualization of global temperature data from the [Climate Change: Earth Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data). The analysis includes data cleaning, exploration, and various visualizations to understand temperature trends over time and across different regions.

## Table of Contents

- [Data Overview](#data-overview)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Visualizations](#visualizations)
  - [Global Temperature Trends](#global-temperature-trends)
  - [Country-Specific Trends](#country-specific-trends)
  - [Seasonal Trends in Germany](#seasonal-trends-in-germany)
  - [Temperature Variations by Latitude](#temperature-variations-by-latitude)
  - [Temperature Variations by Country (Heatmap)](#temperature-variations-by-country-heatmap)
  - [Interactive Map](#interactive-map)
- [Installation](#installation)


## Data Overview

The dataset contains global temperature records by city from 1743 to 2013. The columns in the dataset include:
- `dt`: Date of the temperature recording
- `AverageTemperature`: The average temperature in Celsius
- `AverageTemperatureUncertainty`: The 95% confidence interval around the average temperature
- `City`: The name of the city
- `Country`: The name of the country
- `Latitude`: The latitude of the city
- `Longitude`: The longitude of the city

## Data Cleaning

Steps taken to clean the data:
1. **Remove Missing Values**: Rows with missing values are dropped.
2. **Convert Date Column**: The `dt` column is converted to datetime format.
3. **Extract Year and Month**: Year and month are extracted from the `dt` column for further analysis.

## Exploratory Data Analysis

- **Missing Values**: Count of missing values per column.
- **Unique Values**: Unique values and counts for `City` and `Country`.

## Visualizations

### Global Temperature Trends

Plots of average, minimum, and maximum global temperatures over time (1743-2013).

### Country-Specific Trends

- **Germany**: Average temperature trends in Germany over time.
- **Mongolia**: Average temperature trends in Mongolia over time.
- **Indonesia**: Average temperature trends in Indonesia over time.

### Seasonal Trends in Germany

Seasonal temperature trends in Germany from 2001 to 2013.

### Temperature Variations by Latitude

Scatter plot showing the correlation between latitude and average temperature from 2000 to 2013.

### Temperature Variations by Country (Heatmap)

Heatmap showing average temperatures by country over time for selected countries (2000-2013).

### Interactive Map

An interactive choropleth map showing average temperatures by country.

## Installation

To use the code in this repository, you need the following dependencies:
- Python 3.x
- pandas
- matplotlib
- seaborn
- folium
- geopandas

