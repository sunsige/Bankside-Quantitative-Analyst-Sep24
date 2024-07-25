# Description

Magnificent 7 Backtesting using Double Bollinger Bands strategy

# Table of Contents

# Background

Magnificent 7 Backtesting

The task involves the creation of a backtesting software to evaluate the performance of a specified set of stocks known as the "Magnificent 7" (Microsoft [MSFT], Apple [AAPL], Nvidia [NVDA], Amazon [AMZN], Google [GOOG], Meta [META], Tesla [TSLA]) in the US stock market. The program should employ the Double Bollinger Bands strategy as the basis for trading signals or any other strategy that you deem more applicable. For further details on this strategy, refer to the comprehensive guide available at (https://www.3candlereversal.com/post/kathy-lien-s-double-bollinger-band-strategy).

## Tasks

1. Extract historical price data for the stocks MSFT, AAPL, NVDA, AMZN, GOOG, META, and TSLA using the Yahoo Finance API (yfinance). The data should span from 2013-01-01 to 2023-12-31
2. Implement the Double Bollinger Band indicator to generate buy and sell signals based on the
specified strategy
3. Design a backtesting loop to simulate trading with these signals. Assume an initial capital of
$10,000. The minimum transaction size is set at 1 share per trade
4. Compute the following performance metrics to assess the strategy's effectiveness:

## Performance Metrics

- Total Return
- Annual Return
- Annual Volatility
- Sharpe Ratio
- Sortino Ratio
- Maximum Drawdown