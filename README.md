# Air Quality Analysis: Indian Cities (2015-2024)

## Project Overview

This project presents a comprehensive analysis of air quality trends across 5 major Indian cities over a 10-year period. Using advanced statistical methods and data visualization techniques, the analysis reveals critical insights into pollution patterns, seasonal variations, and city-wise comparisons to inform environmental policy decisions.

## Dataset Information

**Source**: Kaggle Air Quality and Indian Weather Data  
**Time Period**: January 2015 - December 2024  
**Geographic Coverage**: Delhi, Mumbai, Chennai, Kolkata, Bangalore  
**Total Records**: 18,265 daily measurements  
**Key Variables**: PM2.5, PM10, NO2, NH3, CO, SO2, O3, AQI

## Technical Skills Demonstrated

- **Data Processing**: Pandas, NumPy for large dataset manipulation
- **Statistical Analysis**: Hypothesis testing, correlation analysis using SciPy
- **Data Visualization**: Matplotlib, Seaborn for professional charts
- **Time Series Analysis**: Temporal pattern recognition and trend analysis
- **Business Intelligence**: Executive summary and actionable recommendations

## Key Findings

### Statistical Insights
- **Overall Average AQI**: 251.1 (Severe category)
- **Most Polluted City**: Mumbai (AQI: 253.3)
- **Cleanest City**: Bangalore (AQI: 249.8)
- **Seasonal Variation**: Winter months show 5.6 points higher AQI than summer
- **10-Year Trend**: Air quality has worsened by 2.3% over the decade

### Hypothesis Testing Results
- **Weekday vs Weekend**: No statistically significant difference (p = 0.874)
- **City Comparison**: Differences not statistically significant (p = 0.608)
- **Seasonal Effect**: Winter vs Monsoon trends approaching significance (p = 0.065)

## Business Recommendations

### Immediate Actions
- Deploy real-time AQI monitoring systems across all cities
- Implement emergency protocols when AQI exceeds 300
- Focus pollution control efforts during winter months (December-February)

### Strategic Initiatives
- Invest in public transportation infrastructure to reduce vehicular emissions
- Establish green belts in identified high-pollution zones
- Create city-specific pollution reduction targets based on data insights

### Policy Implications
- Implement seasonal emission restrictions during winter months
- Establish industrial activity controls during high pollution periods
- Develop public health advisories for vulnerable populations

## Project Structure

```
Air-Quality-Analysis/
├── data/
│   ├── city_day.csv
│   └── data_description.md
├── notebooks/
│   └── air_quality_analysis.ipynb
├── visualizations/
│   ├── correlation_matrix.png
│   ├── time_series_analysis.png
│   └── city_comparison.png
├── requirements.txt
├── README.md
└── analysis_report.md
```

## Installation and Setup

1. Clone the repository:
```bash
git clone https://github.com/[your-username]/Air-Quality-Analysis.git
cd Air-Quality-Analysis
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:
```bash
jupyter notebook notebooks/air_quality_analysis.ipynb
```

## Analysis Methodology

### Phase 1: Data Understanding and Quality Assessment
- Comprehensive data profiling and validation
- Missing data analysis and treatment strategies
- Data type optimization and memory management

### Phase 2: Exploratory Data Analysis
- Univariate and multivariate analysis
- Distribution analysis of key pollution indicators
- Outlier detection and treatment

### Phase 3: Correlation Analysis
- Pollutant interaction analysis using correlation matrices
- Identification of primary AQI drivers
- Statistical relationship validation

### Phase 4: Time Series Analysis
- Seasonal pattern identification
- Year-over-year trend analysis
- Quarterly and monthly variation studies
- Weekend vs weekday pollution patterns

### Phase 5: Statistical Testing
- Hypothesis testing for group comparisons
- Significance testing using t-tests
- Confidence interval calculations

### Phase 6: Business Intelligence
- Executive summary generation
- Actionable recommendation development
- ROI and impact assessment

## Results and Impact

This analysis provides data-driven insights that can inform:
- Environmental policy development
- Urban planning decisions
- Public health initiatives
- Industrial regulation strategies

The project demonstrates proficiency in end-to-end data analysis, from raw data processing to executive-level business recommendations.

## Technologies Used

- **Python 3.8+**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Static data visualization
- **Seaborn**: Statistical data visualization
- **SciPy**: Statistical analysis and hypothesis testing
- **Jupyter Notebook**: Interactive development environment

## Future Enhancements

- Integration of weather data for enhanced correlation analysis
- Predictive modeling for AQI forecasting
- Interactive dashboard development using Plotly/Dash
- Machine learning models for pollution source identification
- Real-time data pipeline implementation

## Author

Harsha Jain
Data Analytics Enthusiast  
harshajain6114@gmail.com | linkedin.com/in/harsha-jain-b1859b287 | https://github.com/harshajain6114/

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Data source: Kaggle Air Quality Dataset
- Environmental data provided by Central Pollution Control Board of India
- Statistical methodologies inspired by environmental science research
