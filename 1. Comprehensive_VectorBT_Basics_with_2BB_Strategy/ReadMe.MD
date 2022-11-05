#### Improvements to be made to the plot:
The general idea is to make this plot visualization very close to TradingView visualization
* Can we Create custom trace names for the bb_bands `["BB_RSI_Upper","BB_RSI_Middle", "BB_RSI_Lower"]` ?
* Can we move the RSI related labels to the second subplot ?
* Can we have different Symbols for the short entries and short exits?
* I currently have a snapshot of the entire plot as a slider, instead Can we have a Date/Time Slider at the bottom of the stacked plot?
* Instead of plotting in jupyter notebook, can we export the interactive plot (as .html) to for static exploration in a new tab in Chrome Browser?


#### Clarifications:
* Difference in nr. of signals between BBands, RSI creation for individual timeframes in cell #8, versus MTF batch creation in cell #9 using `vbt.talib("BBANDS").run(m5_rsi, skipna=True, timeframe=["5T","30T","1h","4h"], broadcast_kwargs=dict(wrapper_kwargs=dict(freq="5T")))`
