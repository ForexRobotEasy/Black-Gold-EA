# Black Gold EA ReadMe

This ReadMe provides information about the code for the Black Gold EA developed by the Forex Robot Easy Team. Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Code Description

The Black Gold EA is an automated trading system designed for the forex market. It uses a new trending indicator strategy specifically developed for the US market. The code is written in MQL4.

### Input Parameters

The code allows the user to define certain input parameters:

- RiskPercentage: The risk percentage per trade.
- StopLossPercentage: The stop loss percentage per trade.
- TakeProfitPercentage: The take profit percentage per trade.
- MaxTrades: The maximum number of trades allowed simultaneously.

### Global Variables

The code uses the following global variables:

- accountBalance: The current account balance.
- totalTrades: The total number of trades executed.
- trendChanged: A flag to indicate if the trend has changed.

### Trade Structure

The code defines a trade structure with the following properties:

- openPrice: The trade entry price.
- stopLoss: The trade stop loss level.
- takeProfit: The trade take profit level.

### Functions

The code includes several functions to perform specific tasks:

1. IsTrendChanged(): This function checks if the trend has changed. It returns true if the trend has changed, and false otherwise.

2. CloseTradesOnTrendChange(): This function iterates through open trades and closes them if the trend has changed.

3. AdjustRiskLevels(): This function analyzes market conditions and trends to adjust risk levels.

4. ExecuteTrades(): This function executes trades automatically based on predefined conditions.

5. MonitorPositions(): This function monitors and manages open positions.

6. PerformBacktests(): This function performs backtests using historical market data.

7. AnalyzeBacktestResults(): This function analyzes and interprets the results of the backtests.

8. OnStart(): This is the entry point of the program. It initializes variables, performs backtests, and then enters a loop to continuously monitor and manage trades.

## Product Description

The Black Gold EA is an advanced forex trading system developed by the Forex Robot Easy Team. It utilizes a unique trending indicator strategy specifically designed for the US market. This expert advisor (EA) automatically executes trades based on predefined conditions, allowing traders to take advantage of market opportunities without the need for manual intervention.

Key Features:
- New trending indicator strategy for the US market
- Fully automated trading system
- Adjustable risk levels based on market analysis
- Stop loss and take profit levels for each trade
- Maximum number of trades allowed simultaneously
- Backtesting capability to evaluate performance

This product is designed to assist forex traders in maximizing their trading profits by leveraging the power of automation and advanced trading strategies. The Black Gold EA provides a reliable and efficient solution for traders looking to enhance their trading performance in the forex market.

For detailed reviews and trading results of this product, please visit the official developer's website: [Black Gold EA - Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-black-gold-ea-new-trending-indicator-strategy-for-us-market/)

Please note that Forex Robot Easy is not the official developer of this product. We only provide a sample code that demonstrates how the Black Gold EA works. To find the official developer and obtain the full version of this product, please refer to MQL5.
