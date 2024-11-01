

<!DOCTYPE html>
<html lang="en">

<!DOCTYPE html>
<html lang="en">

<body>
    <div>
        <img src="https://media.istockphoto.com/id/1397011551/photo/stack-of-silver-coins-with-trading-chart-in-financial-concepts-and-financial-investment.jpg?s=612x612&w=0&k=20&c=spnvXHk8mNS7GAaz_Um16mllWjHa6oMrTwekQiR8qqU=" alt="Banner Image" class="banner">
    </div>
</body>

# Technical-Indicators-Analysis

This repository contains an in-depth analysis of various financial technical indicators applied to Bitcoin (BTC) trading data from 2018 to 2022 on a 2-hour interval basis. The objective of this project is to explore the effectiveness of multiple indicators for predicting BTC performance and to develop trading signals for optimized return potential.

## Project Overview

Technical indicators are fundamental tools in financial analysis, helping to assess trends, volatility, and trading momentum. This project leverages several technical indicators and statistical techniques to analyze BTC price action and generate signals that can potentially enhance trading strategies. The data has been preprocessed and segmented into specific time intervals to provide actionable insights and a robust framework for further financial analysis.

## Table of contents

- [Dataset](#dataset)
- [Project Goals](#project_goals)
- [Technical Indicators Analyzed](#technical_indicators_analyzed)
- [Data Processing and Analysis](#data_processing_and_analysis)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

## Dataset

- **File:** [btc_18_22_2h.csv](./btc_18_22_2h.csv)
- **Time Period:** January 2018 - December 2022
- **Interval:** 2-hour
- **Attributes:**  The dataset includes time-series data for BTC, comprising open, high, low, close, volume, and additional technical indicator values.

## Project Goals
1. Conduct a comprehensive analysis of technical indicators to assess BTC trading performance.
2. Apply statistical and quantitative techniques to develop signals for optimal entry and exit points.
3. Evaluate different indicator combinations for forecasting accuracy and profitability in BTC trading.

## Technical Indicators Analyzed

The following technical indicators have been calculated and analyzed in the dataset to gauge their performance and predictive power:

- **Moving Averages:** Simple Moving Average (SMA), Exponential Moving Average (EMA)
- **Momentum Indicators:** Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD)
- **Volatility Indicators:** Bollinger Bands, Average True Range (ATR)
- **Trend Indicators:** Parabolic Stop and Reverse (SAR), Ichimoku Cloud
- **Volume Indicators:** Volume-Weighted Average Price (VWAP), On-Balance Volume (OBV)

## Data Processing and Analysis

1. **Data Cleaning and Preprocessing:** The raw BTC data was cleaned and standardized for analysis.
2. **Indicator Calculation:** For each technical indicator, appropriate lookback periods and statistical methods were used to calculate values.
3. **Signal Generation:** Buy and sell signals were developed based on indicator thresholds and historical performance.
4. **Performance Evaluation:** The effectiveness of each indicator and combined strategies was backtested to evaluate predictive accuracy.

## Usage

To replicate the analysis or utilize the dataset:

1. Clone this repository:
```bash
git clone https://github.com/swishtisingh/Technical-Indicators-Analysis.git
cd Technical-Indicators-Analysis
```

2. Install necessary packages:
```bash
pip install pandas numpy matplotlib
```

3. Load the dataset:
```python
import pandas as pd
data = pd.read_csv('btc_18_22_2h.csv')
```

4. **Analysis:** Run calculations on technical indicators using the scripts provided or create custom analyses using the dataset.

## Results

- **Indicator Effectiveness:** Indicators like RSI and MACD showed moderate predictive power for BTC price movements over the 2-hour intervals, particularly in trending markets.
- **Signal Optimization:** Combining SMA and Bollinger Bands with volume-based indicators provided more reliable entry and exit points.
- **Risk Management:** The ATR and VWAP indicators were particularly useful for identifying high-volatility periods, helping to optimize stop-loss placements.

## Contributing

We welcome contributions to improve the analysis or add new features. Please follow these steps to contribute:

1. Fork this repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push to your forked repository and submit a pull request.

## Author
### Srishti Singh
Data Scientist and Machine Learning Enthusiast.<br>
Feel free to connect with me on [LinkedIn.](https://www.linkedin.com/in/srishti-singh-921aa52aa/)

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

### Happy Coding!
