#### Clarifications:
I am planning to segregate long entries/exits and short entries/exits from `pf.trades` using `pf.trades.direction_long` and `pf.trades.direction_short` respectively. I am having the following issues in doing this segregation plots:
1. Specifying the argument `entry_trace_kwargs` and `exit_trace_kwargs` in `pf_2_bb_custom.trades.direction_long[slice_lower : slice_higher].plot().show()` does not work and causes an error?
2. I like the big translucent green and red boxes to show trade entry/exit in profit or loss, but how do I hide `Exit Profit` and `Exit Loss` in the pf_2_bb_custom.trades.direction_short[slice_lower : slice_higher].plot(` plot, not just hide the legend ?
3. Although I see many entries/exits matching position IDs in the `pf_2_bb_custom.trades.direction_short[slice_lower : slice_higher].plot()`, I don't see the `Exit` legend label and marker (`triangle-up`)and I like to know why?
