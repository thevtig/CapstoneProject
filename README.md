# Empirical Study of Portfolio Construction and Risk Assessment

Welcome to the repository for a comprehensive capstone project examining portfolio construction and risk assessment through randomized stock selection. Utilizing sophisticated machine learning techniques and statistical models, this project provides a deep dive into the performance and risk of diverse stock portfolios.

## Project Overview

This study aims to dissect the intricacies of stock portfolio performance and associated risks by constructing portfolios from a randomized selection of stocks. It uses a dataset of 100 stocks to create ten unique portfolios in each of five simulation runs. The project utilizes machine learning to evaluate and compare these portfolios, identifying which combinations offer the most advantageous risk-adjusted returns.

## Data Collection and Preprocessing

We have gathered historical stock data, including prices and volumes, for 100 stocks using the `yfinance` Python library. A meticulous preprocessing phase ensures the data is clean, normalized, and consistent across the board.

## Methodology

Our comprehensive methodology includes:

- **Randomized Portfolio Creation:** We implemented an algorithm to randomly select 10 stocks, ensuring a diversified and representative portfolio creation process.
- **Portfolio Performance Evaluation:** Portfolios are assessed using returns and Sharpe ratios, while ARIMA models project future performance based on historical data.
- **Risk Assessment:** Portfolio risk is quantified through the standard deviation, Value at Risk (VaR), and Conditional Value at Risk (CVaR).
- **Simulation and Iteration:** The process involves five simulation runs to generate and evaluate new groups of portfolios, each iteration enriching the analytical narrative.
- **Comparative Analysis and Selection:** We compare portfolios to ascertain the top performers, using criteria that strike a balance between high returns and low risk.

## Tools and Technologies

The project is powered by Python, with key libraries such as `yfinance` for data acquisition, `pandas` for data manipulation, `numpy` for numerical analysis, and `matplotlib` for visualization.

## Installation and Usage

Complete instructions for setting up the environment and executing the code are provided, allowing users to replicate the study's outcomes and delve into the performance and risk assessment of randomized stock portfolios.

## Results of the Analysis for Portfolio Construction and Risk Assessment

Our simulation yielded intriguing insights, showcasing the variability and potential of diversified portfolios. Across the simulation runs, we noticed:

- **Portfolio Risk:** We observed a spectrum of risk profiles, from the more volatile portfolios containing stocks like NFLX, INTC, and JPM, to the less volatile ones composed of stocks such as HD, GOOGL, and PFE.

- **Annual Returns:** The annual returns ranged dramatically, with portfolios containing NVDA, ROKU, and INTC leading with high returns, suggesting that random selection can occasionally construct portfolios that significantly outperform the market.

- ### Detailed Insights from Specific Simulation Runs

- **Run 1 Insights:** The portfolio risk ranged from approximately 22.59% for a portfolio with stocks like HD and GOOGL to 33.85% for a portfolio including NFLX and INTC, highlighting the diversity in risk due to different stock compositions.

- **Run 2 Highlights:** The returns analysis for Run 2 emphasized the stark contrasts in portfolio performance, with some like GOOGL and ADBE bringing in an average annual return of around 45.72%, significantly outpacing others such as PEP and V, which posted close to 11.19%.

- **Run 3 and Beyond:** Subsequent runs continued to underscore the relationship between selected stocks and portfolio outcomes. For instance, portfolios with a tech-heavy composition tended to show both higher risk and higher potential returns.

## ARIMA Model Summary and Forecast for INTC
The ARIMA model summary for INTC revealed an AR coefficient of 0.1224 and an MA coefficient of -0.9995, hinting at the importance of the previous term and the error term in predicting future values. The model's adequacy is further evidenced by a low p-value for the MA term and a satisfactory Ljung-Box test result, suggesting that the residuals are independently distributed. Heteroskedasticity seems to be under control, as indicated by the H statistic, and the forecast for the next five periods shows a slight upward trend in the predicted mean.



## Conclusion

This project emphasizes the significance of portfolio diversity and the need for rigorous risk assessment in investment strategy formulation. By blending random selection with methodical evaluation, the study furnishes valuable insights, allowing investors and financial analysts to fine-tune their approaches for optimized portfolio performance.

The findings from this empirical study are not only academically intriguing but also carry practical implications for portfolio management, challenging traditional investment paradigms and advocating for a data-centric approach to understanding market complexities.

---

