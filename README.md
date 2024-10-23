# Empirical Methods in Finance

## Project Overview
This project applies empirical finance methods to analyze the financial performance of various assets, including Mastercard (MA), Goldman Sachs (GS), American Express (AXP), Morgan Stanley (MS), and Visa (V). The analysis includes return calculations, statistical tests, and the development of a pairs trading strategy. The key sections of the project are:

1. **Descriptive Statistics**: Computation of annualized mean, variance, skewness, kurtosis, minimum, and maximum for both daily and weekly simple and log returns.
2. **Stationarity Testing**: Tests to check whether time series data is stationary using the Augmented Dickey-Fuller (ADF) test and autoregressive models.
3. **Cointegration Analysis**: Testing for long-term relationships between asset pairs to identify potential arbitrage opportunities.
4. **Pairs Trading Strategy**: Development and evaluation of a pairs trading strategy based on cointegrated assets.

## Main Topics Covered

### 1. Descriptive Statistics
- **Daily and Weekly Returns**: Simple and log returns are calculated for both daily and weekly frequencies.
- **Statistical Measures**: For both daily and weekly returns, the following statistics are computed:
  - Annualized Mean
  - Annualized Variance
  - Skewness
  - Kurtosis
  - Minimum and Maximum Returns

### 2. Stationarity Testing
- **ADF Test**: The Augmented Dickey-Fuller test is applied to assess the stationarity of financial time series data, which is critical for identifying potential cointegration between assets.
- **Autoregressive Models**: Fitting autoregressive (AR) models to the log-transformed prices to further test for stationarity.

### 3. Cointegration Analysis
- **Testing for Cointegration**: The Engle-Granger two-step method is used to test for cointegration between asset pairs, identifying assets that move together in the long run. This is essential for building the pairs trading strategy.

### 4. Pairs Trading Strategy
- **Strategy Development**: Based on the cointegration results, a pairs trading strategy is developed. The strategy involves:
  - Monitoring the spread between two cointegrated assets.
  - Placing trades when the spread deviates significantly from the mean (mean-reversion strategy).
  - Evaluating the performance of the strategy in terms of profit and risk.

## Key Insights
- **Descriptive Statistics**: Analysis reveals important characteristics of the financial assets, including volatility (variance), return asymmetry (skewness), and the presence of extreme returns (kurtosis).
- **Stationarity and Cointegration**: Testing shows that certain asset pairs exhibit a long-term relationship, enabling the development of a pairs trading strategy.
- **Pairs Trading Strategy**: The strategy exploits deviations from the long-term equilibrium between two cointegrated assets, offering a potential low-risk trading opportunity.

