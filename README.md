# Comparative Stock Performance and Time Series Analysis

This project investigates the performance of stocks such as Apple and Microsoft over a specified period, along with an exploration of time-series concepts applied to weather data. The analysis covers stock trends, volatility, and performance comparison, as well as an examination of temperature data across multiple cities to observe patterns and correlations in time-series data.

## Project Overview

### Stock Performance Analysis

- **Time-Series Analysis**: Investigates trends in Apple and Microsoft stock prices from 2019 to 2023.
- **Downsampling & Smoothing**: Examines the effect of downsampling stock data on reducing noise and identifying long-term trends.
- **Return Rate Analysis**: Explores the concept of monthly returns and patterns that emerge over time.
- **Volatility Comparison**: Compares the volatility of Microsoft and Apple stock prices.


![image](https://github.com/user-attachments/assets/d1db5ce7-868a-4568-bad9-bef489be76f1)
![image](https://github.com/user-attachments/assets/ccbca9d8-1b80-4893-8906-eff408986ee6)

  
### Time-Series Analysis Applied to Weather Data

In addition to stock performance analysis, this project applies time-series concepts to weather data, specifically analyzing temperature trends across multiple cities. This section was designed to explore broader time-series principles in a different context.

- **City Comparison**: Analyzes temperature data for cities like Edmonton, Calgary, and Buenos Aires.
- **Seasonality and Cyclical Patterns**: Observes seasonal temperature fluctuations over time in different cities.
- **Autocorrelation**: Explores how temperature patterns correlate over time, including lagged correlations between cities (e.g., Edmonton and Buenos Aires).

## Key Questions Addressed

1. **Stock Trends**: What trends can be observed in the stock prices of Apple and Microsoft over time?
2. **Downsampling Impact**: How does downsampling affect time-series data, and what time-scale is most appropriate for analysis?
3. **Return Rates**: Why does the first monthly return rate result in NaN, and what insights can be gained from return rate patterns?
4. **Temperature Patterns**: What are the observed seasonal patterns in the temperature data across different cities, and how do they compare?
5. **Cross-City Correlations**: How do temperature trends correlate between cities over time, especially when considering different hemispheres?

## Technologies Used

- **Python**
- **Pandas**: For data manipulation and time-series analysis.
- **Matplotlib & Seaborn**: For data visualization, including stock trends and temperature patterns.
- **NumPy**: For numerical computations and autocorrelation analysis.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/time-series-analysis.git
