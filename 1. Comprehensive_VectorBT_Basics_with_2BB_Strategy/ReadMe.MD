#### Clarifications:
1. What does the `.real` do in the code `m5_rsi = vbt.talib("RSI", timeperiod = rsi_period).run(m5_data.get("Close"), skipna=True).real`?
2. Right now, even though I have markers I cannot make out which extry/exit belongs to which trade/order, so can we add dotted lines in the plot to connect an entry and exit of a trade order, that we would see in MT5?
3. How to access floating equity and balance after the simulation or it the same as `PnL` plot that I have at the end?
4. You show some signal and order stats (like duration of trades etc.) that we can do in this [Signals Development](https://vectorbt.pro/pvt_5ff983ef/tutorials/signal-development/#duration) Tutorials Page. Can you give a list of suggestions (with code) about different types of order or signal analytics that can we do to make this notebook more complete / comprehensive?
