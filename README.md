# Magnificent 7 Backtesting

This project employs the Double Bollinger Bands strategy as the basis for trading signals involves the creaton of a backtesting software to evaluate the performance of the Magnificent 7 in the US stock market.

1. Extract historical price data for the stocks MSFT, AAPL, NVDA, AMZN, GOOG, META, and TSLA
using the Yahoo Finance API (yfnance). The data should span from 2013-01-01 to 2023-12-31
2. Implement the Double Bollinger Band indicator to generate buy and sell signals based on the
specifed strategy
3. Design a backtestng loop to simulate trading with these signals. Assume an inital capital of
$10,000. The minimum transacton size is set at 1 share per trade
4. Compute the following performance metrics to assess the strategy's efectveness:
 - Total Return
 - Annual Return
 - Annual Volatlity
 - Sharpe Rato
 - Sortno Rato
 - Maximum Drawdown
