**Problem Statement:**
Develop a stock price prediction model to strategize buy/sell decisions for a portfolio consisting of 10 selected stocks from various industries. Utilize historical daily data obtained from the AlphaVantage API to run a simulation for 2 weeks, starting with $10,000 cash and executing trades based on the prediction model.

**Explanation:**
This project involves utilizing historical daily stock price data obtained from AlphaVantage API to predict stock price movements and formulate buy/sell strategies for a diversified portfolio comprising the following 10 stocks from different industries - Apple Inc. (AAPL), Microsoft Corporation (MSFT), Johnson & Johnson (JNJ), Pfizer Inc. (PFE), The Procter & Gamble Company (PG), The Coca-Cola Company (KO), JPMorgan Chase & Co. (JPM), Visa Inc. (V), Exxon Mobil Corporation (XOM), and Chevron Corporation (CVX). The simulation will track trading decisions and calculate the final portfolio value and strategy Sharpe ratio.

**Steps:**
1. **Get API Key:** Obtain an API key from AlphaVantage to access historical daily stock price data.
2. **Download Data:** Retrieve historical daily data for the 10 selected stocks from the API.
3. **Simulation:** Create a simulation environment to execute buy/sell decisions based on stock price predictions over a 2-week period.
4. **Evaluate Strategy:** Calculate the final portfolio value (cash + current price of stocks * positions) and determine the Sharpe ratio of the trading strategy.

**Business Question/Simulation:**
Answer the following questions:
- What is the final portfolio value after 2 weeks of trading based on the prediction strategy?
- What is the Sharpe ratio of the trading strategy, indicating risk-adjusted performance?

**Metrics for Quality:**
Metrics to assess the quality of the output may include:
- Final portfolio value indicating the effectiveness of the prediction strategy.
- Sharpe ratio reflecting the risk-adjusted returns of the trading strategy.
- Accuracy of stock price predictions and corresponding buy/sell decisions.