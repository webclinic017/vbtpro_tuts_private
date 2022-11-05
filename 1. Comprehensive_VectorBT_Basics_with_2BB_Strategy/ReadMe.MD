#### Improvements to be made to the plot:
The general idea is to make this plot visualization very close to TradingView visualization
* Create custom trace names for the bb_bands `["BB_RSI_Upper","BB_RSI_Middle", "BB_RSI_Lower"]`
* Move the RSI related labels to the second subplot
* Different Symbols for the short entries
* Date/Time Slider at the bottom of the stacked plot
* Instead of plotting in jupyter notebook, can we export the interactive plot (as .html) to for static exploration in a Chrome Browser tab


#### Clarifications:
* Difference between individual BBands, RSI creation, versus mtf batch creation using `vbt.talib("BBANDS").run(m5_rsi, skipna=True, timeframe=["5T","30T","1h","4h"], broadcast_kwargs=dict(wrapper_kwargs=dict(freq="5T")))`