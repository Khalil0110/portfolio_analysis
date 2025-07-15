# 📈 Portfolio Risk Analysis: Bull vs Bear Market Comparison

This project analyzes the performance and risk of a portfolio of 5 major tech stocks and the S&P 500 index across two different market regimes — a **bull market (2016–2019)** and a **bear market (COVID crash, 2020)**.

It includes comprehensive risk analysis using:
- Parametric & Historical VaR
- Conditional VaR (CVaR)
- Monte Carlo simulation
- Drawdown analysis
- EWMA & GARCH volatility models
- Fisher information and Cornish-Fisher adjustment

---

## Tools Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `yfinance` for financial data
- `scipy`, `arch` for statistical modeling

---

## Portfolio

The portfolio contains:
- 📊 Stocks: AAPL, MSFT, GOOGL, AMZN, TSLA
- 🏦 Index: S&P 500 (^GSPC)
- ⚖️ Weighted allocation (can be adjusted in notebook)

---

## Risk Metrics Compared

| Metric         | Description                                 |
|----------------|---------------------------------------------|
| Annual Return  | Total return over the period                |
| Volatility     | Standard deviation of returns               |
| Sharpe Ratio   | Risk-adjusted performance                   |
| VaR (5%)       | Potential loss under normal conditions      |
| CVaR (5%)      | Expected loss in worst-case 5% scenarios    |
| Cornish-Fisher | Adjusted VaR for non-normality              |
| EWMA Vol       | Time-decayed volatility                     |
| Monte Carlo    | Simulated future price paths                |
| Drawdown       | Largest peak-to-trough loss                 |
