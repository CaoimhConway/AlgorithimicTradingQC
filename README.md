# Algorithmic Trading Strategies for QuantConnect

This is a collection of algorithims created in **Python** created in order to research, backtest, and develop trading and investment strategies. Intended for use with the open-source platform QuantConnect. 


## Strategies

# Asset Class Momentum
[Report](https://www.quantconnect.com/reports/434dbef842cee46850dbfba07cc4534d)

This strategy considers 5 ETFs (SPY – US stocks, EFA – foreign stocks, BND – bonds, VNQ – REITs, GSG – commodities). It then picks 3 ETFs with the strongest 12-month momentum, weighting them equally, and rebalances once a month. This strategy has a CAGR of 9.8%, a max drawdown of 70.5%, and a Sharpe ratio of .49.


# All Weather Portfolio 
[Report](https://www.quantconnect.com/reports/1bb306edc363c0c80b9580744d8dfc26)

The "All Weather" Portfolio, popularized by hedge fund Ray Dalio, is designed to minimize drawdowns through financial downturns. It is composed of 40% long-term bonds, 30% stocks, 15% intermediate-term bonds, 7.5% gold, and 7.5% commodities. The portfolio rebalances itself to these levels once a year. This strategy has a CAGR of 9.2%, a max drawdown of 21.7%, and a Sharpe ratio of .88.

