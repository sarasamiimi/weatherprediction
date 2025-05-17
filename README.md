#Weather Data Analysis

A Python project that analyzes historical weather data to extract insights like average monthly temperatures, precipitation types, and extreme weather conditions.

##Dataset

The dataset used is `weatherHistory.csv`, which contains several years of hourly weather data including:

- Temperature (°C)
- Precipitation Type
- Formatted Date
- Humidity, Wind Speed, and more

## What this script does

- Parses and extracts year & month from the datetime column
- Handles missing values (`Precip Type`)
- Drops irrelevant columns
- Calculates:
  - Average temperature per month
  - Distribution of precipitation types
  - Hottest and coldest recorded days

## Requirements

Install dependencies using:

```bash
pip install pandas matplotlib seaborn
