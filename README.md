
# Portfolio Optimization 📈

Welcome to the **Portfolio Optimization** project! This Python-based tool assists investors in optimizing their stock portfolios using historical data. By analyzing the performance of selected stocks over time, the tool offers insights into the best allocation strategy to maximize returns and minimize risk.

## 🚀 Features

- **Historical Data Retrieval**: Gathers historical adjusted close prices of selected stocks from Yahoo Finance.
- **Visual Analysis**: Graphically displays the adjusted closing price history of stocks in the portfolio.
- **Performance Metrics**: Computes daily simple returns, annual variance, and volatility of the portfolio.
- **Portfolio Optimization**: Uses the `PyPortfolioOpt` library to optimize the portfolio based on the Sharpe ratio.
- **Discrete Allocation**: Suggests a specific allocation of stocks based on available portfolio value.
  
## 📁 File Structure

- 📄 `Python Portfolio Optimization.py`: The main script containing the logic for data retrieval, analysis, visualization, and portfolio optimization.

## 🔧 Setup & Execution

1. Install the required Python libraries:
   ```bash
   pip install pandas_datareader pypfopt pulp
   ```
2. Execute the script:
   ```bash
   python "Python Portfolio Optimization.py"
   ```

## 🧠 Technical Insights

- **Data Source**: Historical stock data is sourced from Yahoo Finance using the `pandas_datareader` library.
- **Portfolio Analysis**: The script calculates metrics like daily simple returns, annual variance, and volatility to evaluate the portfolio's performance.
- **Optimization Technique**: The portfolio is optimized using the Sharpe ratio with the help of the `PyPortfolioOpt` library.
- **Discrete Allocation**: The script suggests a specific allocation of stocks to ensure an optimal spread of funds across the selected stocks.

## 🧪 Testing

1. Execute the script as detailed above.
2. Examine the visual representation of stock price history and other printed metrics.
3. Modify the list of stocks or other parameters in the script to see how the optimization results change.
