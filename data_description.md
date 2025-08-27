
# Data Description

## Dataset Overview

This directory contains the air quality dataset used for the comprehensive analysis of pollution patterns across Indian cities.

## File Structure

### city_day.csv
**Description**: Daily air quality measurements for 5 major Indian cities  
**Size**: 18,265 records  
**Time Range**: January 1, 2015 - December 31, 2024  
**Geographic Coverage**: Delhi, Mumbai, Chennai, Kolkata, Bangalore

## Column Descriptions

| Column Name | Data Type | Description | Unit |
|-------------|-----------|-------------|------|
| City | String | Name of the city | - |
| Datetime | Date | Date of measurement | YYYY-MM-DD |
| PM2.5 | Float | Particulate Matter 2.5 | μg/m³ |
| PM10 | Float | Particulate Matter 10 | μg/m³ |
| NO | Float | Nitric Oxide | μg/m³ |
| NO2 | Float | Nitrogen Dioxide | μg/m³ |
| NOx | Float | Nitrogen Oxides | ppb |
| NH3 | Float | Ammonia | μg/m³ |
| CO | Float | Carbon Monoxide | mg/m³ |
| SO2 | Float | Sulfur Dioxide | μg/m³ |
| O3 | Float | Ozone | μg/m³ |
| Benzene | Float | Benzene | μg/m³ |
| Toluene | Float | Toluene | μg/m³ |
| Xylene | Float | Xylene | μg/m³ |
| AQI | Float | Air Quality Index | Index Value |
| AQI_Bucket | String | AQI Category | Good/Satisfactory/Moderate/Poor/Very Poor/Severe |

## Air Quality Index (AQI) Categories

| AQI Range | Category | Health Impact |
|-----------|----------|---------------|
| 0-50 | Good | Minimal impact |
| 51-100 | Satisfactory | Minor breathing discomfort to sensitive people |
| 101-200 | Moderate | Breathing discomfort to people with lung disease |
| 201-300 | Poor | Breathing discomfort to most people on prolonged exposure |
| 301-400 | Very Poor | Respiratory illness on prolonged exposure |
| 401-500 | Severe | Affects healthy people and seriously impacts those with existing diseases |

## Data Quality Notes

- **Completeness**: No missing values in the dataset
- **Consistency**: All dates follow YYYY-MM-DD format
- **Accuracy**: Data sourced from official government monitoring stations
- **Coverage**: Consistent daily measurements across all cities and time periods

## Usage Guidelines

1. **Data Loading**: Use pandas.read_csv() with date parsing for Datetime column
2. **Memory Optimization**: Consider data types optimization for large-scale analysis
3. **Time Series Analysis**: Convert Datetime to pandas datetime index for time-based operations
4. **City Comparison**: Ensure proper grouping by City column for comparative analysis

## Source Attribution

- **Primary Source**: Central Pollution Control Board (CPCB), India
- **Secondary Source**: Kaggle Air Quality Dataset
- **Last Updated**: December 2024
- **Update Frequency**: Daily (for real-time applications)

## Data Preprocessing Notes

The following preprocessing steps were applied during analysis:
1. Date format standardization
2. Numeric data type validation
3. Outlier detection and validation
4. Statistical distribution analysis
5. Temporal consistency checks