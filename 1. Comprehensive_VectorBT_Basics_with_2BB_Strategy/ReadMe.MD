#### Clarifications:
1. Is there some built in function of  `vbt.pf.plot()` variant which plots (using plotly) the `equity` and `balance` on Y-axis & time on the X-axis and also draws a max drawdown line on the equity and balance? Currently, I am only able to do this using matplotlib `pf.trades.records_readable.PnL.cumsum().plot()` which doesn't look great.
2. Where do I see the Max Drawdown Duration as being 282 days in the above `pf.stats()`, can we see it in the Orders plot or the matplotlib PnL `pf.trades.records_readable.PnL.cumsum().plot()` Plot _as a dotted line that connects the highest point of equity and lowest point of equity_ ?

Some Resources for Calculating and plotting Max Drawdown:
1. https://medium.com/cloudcraftz/measuring-maximum-drawdown-and-its-python-implementation-99a3963e158f
2.https://quant.stackexchange.com/questions/55130/global-maximum-drawdown-and-maximum-drawdown-duration-implementation-in-python
3. https://stackoverflow.com/questions/22607324/start-end-and-duration-of-maximum-drawdown-in-python

