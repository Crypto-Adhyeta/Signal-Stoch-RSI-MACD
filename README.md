# Signal Stoch+RSI+MACD
 Pine Script signal generator based on 3 indicators StochasticRSI & RSI & MACD

Combined signal generator based of 3 indicators inspired by the youtube video "Highly Profitable Stochastic + RSI + MACD Trading Strategy (Proven 100x)" of "Data Trader". It generates 2 signals for Long and Short position entry.

The Long entry alert is fired when:
Price increase is indicated by Stochastic which starts to rise up from Oversold area
RSI is in uptrend phase
Positive momentum is confirmed by MACD line above Signal line
all three indicators are giving positive signal and Stochastic still hasn't reached Overbought area, the alert is fired

The Short entry alert is fired when:
Price decrease is indicated by Stochastic which starts to drop down from Overbought area
RSI is in downtrend phase
Negative momentum is confirmed MACD line below Signal line
all three indicators are giving positive signal and Stochastic still hasn't reached Oversold area, the alert is fired

The recommendation how to set up Take Profit & Stop Loss is explained in the video. Basically Stop Loss should be set following nearest swing-low and Take Profit shoulb be set to 3 times of Stop Loss value.