# Google Trends & Financial Market Analysis

## Project Overview

This project analyzes Google search trends alongside financial and economic indicators using Python.

The analysis focuses on three datasets:

- Tesla Google search interest and Tesla stock price
- Bitcoin price and trading volume
- Unemployment-benefit Google search interest and U.S. unemployment rate

## Objectives

- Analyze Tesla search interest and stock price trends.
- Analyze Bitcoin price and trading-volume trends.
- Examine unemployment-related search interest alongside the unemployment rate.
- Perform correlation analysis.
- Apply rolling averages and percentage-change analysis.
- Create clear data visualizations and extract data-driven insights.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Google Trends data
- Financial market data

## Analysis Performed

### Data Cleaning
- Checked dataset dimensions and data types
- Checked missing values
- Checked duplicate records
- Converted date columns to datetime
- Sorted datasets chronologically
- Removed one incomplete Bitcoin record

### Exploratory Data Analysis
- Tesla search interest
- Tesla stock price
- Bitcoin closing price
- Bitcoin trading volume
- Unemployment search interest
- U.S. unemployment rate

### Time-Series Analysis
- Monthly Bitcoin aggregation
- 6-month rolling averages
- 30-day Bitcoin rolling average

### Statistical Analysis
- Correlation analysis
- Percentage-change analysis
- Bitcoin daily return volatility

## Datasets

### Tesla
Columns:
- `MONTH`
- `TSLA_WEB_SEARCH`
- `TSLA_USD_CLOSE`

### Bitcoin
Columns:
- `DATE`
- `CLOSE`
- `VOLUME`

### Unemployment
Columns:
- `MONTH`
- `UE_BENEFITS_WEB_SEARCH`
- `UNRATE`

## Important Considerations

Google Trends represents relative search interest rather than absolute search volume.

Correlation measures the strength and direction of a relationship but does not establish causation.

The datasets have different time frequencies and coverage periods, so appropriate time aggregation is used where required.

## Project Structure

```text
Google-Trends-Financial-Market-Analysis/
│
├── data/
├── notebook/
├── README.md
└── requirements.txt
