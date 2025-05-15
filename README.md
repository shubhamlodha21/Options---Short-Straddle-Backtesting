# Options Short-Straddle-Backtesting
Short Straddle Backtesting

# 📈 NIFTY Short Straddle Backtesting Framework

This project implements a backtesting engine for the **Short Straddle options trading strategy** on **NIFTY** index option data using intraday tick-level CSV files. It allows users to test the profitability and performance metrics of selling At-The-Money (ATM) CE and PE options and managing positions with a stop-loss and end-of-day exit.

## 🚀 Features

- Intraday options data handling from CSVs.
- Dynamic ATM strike detection based on early market prices.
- Simulated short straddle with:
- Fixed entry and exit times.
- Configurable stop-loss.
- Realistic slippage and brokerage handling.
- Detailed trade logs with PnL.
- Performance analytics: win rate, CAGR, Sharpe ratio, max drawdown.
- Daily capital and equity curve tracking.
- Export of results to CSV.
- 
📊 Output Metrics
The script prints and exports:

Daily trade logs: 
- entry/exit prices
- PnL
- exit reason
  
Key metrics:
- Win rate
- Total return
- CAGR
- Sharpe ratio
- Max drawdown

Example Output:
==== Performance Summary ====
- Total Days     : 20
- Total Return   : ₹40,000.00 (4.00%)
- Max Drawdown   : ₹10,500.00 (1.05%)
- CAGR           : 48.32%
- Sharpe Ratio   : 1.72
