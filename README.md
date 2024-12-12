
# Financial Metrics Analysis and Visualization of Stocks


## Overview
This project focuses on evaluating and visualizing key financial metrics for four major stocks: Apple (AAPL), Tesla (TSLA), Disney (DIS), and AMD. The analysis includes various statistical measures such as daily and cumulative returns, kurtosis, skewness, Sharpe ratio, as well as visualizations like histograms, pairplots, and a correlation matrix. Tools like QuantStats and Seaborn were used for financial analysis and visualization.

## Key Highlights
- Financial Metrics:
  - Daily and Cumulative Returns: Analyzed daily returns and calculated cumulative returns for each stock.
  - Kurtosis and Skewness: Evaluated the distribution shape of the returns for each stock using kurtosis and skewness values.
  - Sharpe Ratio: Computed the Sharpe ratio to assess risk-adjusted returns for each stock.
- Visualizations:
  - Histograms: Plotted histograms for each stock to visualize the distribution of daily returns.
  - Pairplots: Created pairwise relationships between the returns of the stocks to assess correlations visually.
  - Correlation Matrix: Generated a heatmap showing correlations between the stocks' daily returns.
- Tools Used:
  - QuantStats: Used for calculating and analyzing financial metrics such as cumulative returns, Sharpe ratio, etc.
  - Seaborn: Used for generating statistical visualizations like pairplots, histograms, and heatmaps.

##  Dependencies
Install the following Python libraries to run this project:

- pandas
- numpy
- matplotlib
- seaborn
- quantstats
- yfinance
## Methodology
- Data Collection:
  - Stock data for AAPL, TSLA, DIS, and AMD was retrieved using Yahoo Finance via the yfinance library.
- Preprocessing:
  - Calculated daily returns from adjusted close prices.
  - Cleaned the data by handling missing values and removing unnecessary columns.
- Financial Metric Calculation:
  - Calculated cumulative returns, kurtosis, skewness, and Sharpe ratio for each stock.
- Visualization:
  - Plotted histograms of daily returns.
  - Created pairplots to visualize correlations between stocks.
  - Generated a correlation matrix heatmap to assess relationships between stock returns.
- Evaluation:
  - Analyzed metrics to compare the risk-return profiles of the stocks.
## Conclusion
This project provides an in-depth analysis of four major stocks, evaluating their financial metrics and visualizing their performance. The use of QuantStats made it easy to generate insightful statistical analysis and visual representations. The evaluation of key metrics like daily returns, cumulative returns, kurtosis, skewness, and Sharpe ratios allows for better decision-making in stock selection and portfolio management.
## Future Improvements

- Additional Stocks: Include more stocks for a diversified portfolio analysis.
- Advanced Visualizations: Explore interactive dashboards using Plotly or Dash for better user engagement.
- Risk Analysis: Further assess the risks of stock investments using tools like Value at Risk (VaR) or Monte Carlo simulations.
##  Dependencies
Install the following Python libraries to run this project:

- pandas
- numpy
- matplotlib
- seaborn
- quantstats
- yfinance