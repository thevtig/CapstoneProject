
# Empirical Study of Portfolio Construction and Risk Assessment

This repository hosts the code for a capstone project focused on the empirical study of portfolio construction and risk assessment using randomized stock selection. The project leverages machine learning techniques to evaluate the performance and risk of portfolios composed of randomly selected stocks. Through the application of statistical and machine learning models, including ARIMA for time series forecasting, the project aims to offer insights into the effectiveness of randomized stock portfolios.

## Project Overview

The objective of this study is to explore the performance and risk associated with portfolios constructed from a randomized selection of stocks. Utilizing a dataset of 100 stocks, the project creates ten distinct portfolios in each simulation, with a total of five simulations conducted. The project applies machine learning techniques to assess and compare the performance and risk of these portfolios, aiming to identify the configurations that yield the best risk-adjusted returns.

## Data Collection and Preprocessing

Historical stock data, including prices, volumes, and other financial metrics for 100 stocks, are sourced using the `yfinance` Python library. The data undergoes a thorough preprocessing phase to ensure cleanliness, normalization, and consistency across the datasets.

## Methodology

The methodology encompasses several key phases:

- **Randomized Portfolio Creation:** A random shuffling algorithm selects 10 stocks to create each portfolio, with the process ensuring diversity and representativeness.
- **Portfolio Performance Evaluation:** Performance is evaluated using metrics such as return rates and Sharpe ratios, with ARIMA models employed to forecast future performance based on historical data.
- **Risk Assessment:** The project assesses portfolio risk by calculating standard deviation, Value at Risk (VaR), and Conditional Value at Risk (CVaR), among other metrics.
- **Simulation and Iteration:** Five simulations are run to generate and evaluate new groups of portfolios, with each iteration contributing to the overall analysis.
- **Comparative Analysis and Selection:** The portfolios are compared to determine the best performers, using criteria that balance high returns against low risk.

## Tools and Technologies

The project utilizes Python as the primary programming language, with key libraries including `yfinance` for data retrieval, `pandas` for data manipulation, `numpy` for numerical calculations, and `matplotlib` for visualization.

## Installation and Usage

Instructions for setting up the environment and running the code are provided, ensuring users can replicate the study's findings and explore the performance and risk assessment of randomized stock portfolios.

## Conclusion

This capstone project aims to bridge the gap between complex machine learning techniques and practical investment strategies. By analyzing randomized portfolios through empirical data and ML models, the study provides actionable insights for investors and financial analysts looking to optimize portfolio performance in a systematic and informed manner.

---
