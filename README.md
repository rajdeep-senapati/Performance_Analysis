# Binance Account Performance Analysis and Ranking (BAPAR)

## Overview
The **Binance Account Performance Analysis and Ranking (BAPAR)** project analyzes historical trade data from various Binance accounts over a 90-day period. The primary objective is to calculate key financial metrics, rank accounts based on a weighted scoring system, and provide a top 20 list of the best-performing accounts. This helps users understand account performance and identify the most profitable traders based on quantitative metrics.

## Dataset Information
The dataset consists of:
- **Port_IDs**: Unique identifiers for accounts.
- **Trade_History**: Historical trade records with details such as:
  - Timestamp
  - Asset
  - Trade side (BUY/SELL)
  - Trade price
  - Trade volume

The dataset captures 90 days of trading activity across multiple accounts.

## Objective
1. **Analyze** the dataset to compute financial metrics for each account.
2. **Rank** accounts using a weighted scoring system based on performance metrics.
3. **Identify** the top 20 best-performing accounts based on quantitative data.

## Metrics Calculated
The following financial metrics are computed for each account:
- **ROI (Return on Investment)**: Measures investment profitability.
- **PnL (Profit and Loss)**: Total profit or loss generated.
- **Sharpe Ratio**: Measures risk-adjusted return.
- **MDD (Maximum Drawdown)**: Largest peak-to-trough drop in account value.
- **Win Rate**: Percentage of winning trades.
- **Win Positions**: Number of profitable trades.
- **Total Positions**: Total number of trades executed.

## Steps to Complete the Task
### 1. Data Exploration and Cleaning
- **Loaded and inspected the dataset**: Checked for missing values, duplicates, and inconsistencies.
- **Handled missing values**: Imputed or removed missing data points where necessary.
- **Preprocessed timestamps**: Standardized the timestamp format for time-series analysis.

### 2. Feature Engineering
- **Calculated financial metrics**:
  - Computed ROI, PnL, Sharpe Ratio, MDD, Win Rate, and other key performance indicators for each account.
- **Determined feature importance**:
  - Assessed the relative importance of each metric using statistical methods and domain knowledge.
- **Applied a weighted scoring system**:
  - Assigned different weights to each metric based on its significance (e.g., higher weight for Sharpe Ratio and ROI).

### 3. Ranking Algorithm
- Developed an algorithm to **rank accounts** based on their weighted performance scores.
- Sorted accounts in descending order to **identify top performers**.

### 4. Documentation
- Compiled a **concise report** explaining:
  - Methodology
  - Findings
  - Assumptions

## How to Use
1. Ensure the dataset is available and formatted correctly.
2. Run the provided scripts to preprocess data and calculate performance metrics.
3. Execute the ranking algorithm to generate the **top 20 list** of best-performing accounts.
4. Review the results and insights provided in the output report.

## Assumptions and Considerations
- The **dataset is assumed to be complete** and accurately recorded.
- Metrics like **Sharpe Ratio** are computed based on historical trade data without external market conditions.
- The **weighted scoring system is subjective** and may need adjustments based on real-world evaluation.

## Conclusion
This project provides a **quantitative approach** to ranking Binance accounts based on their trading performance. By leveraging financial metrics and a weighted scoring system, traders and analysts can identify top-performing accounts and gain insights into effective trading strategies.

