# deep_learning

## Answers To questions

### Which Model has a lower loss?

The Model with the lowest loss is when the stock price is used as the predictor. 

### Which Model Tracks the actual values better over time?

Based on the plot, it would seem that past prices are better at predicting the future prices in comparison to the FNG values.

### Which window size words best for the model?

at a window size of 1, the FNG model has a loss of .0770 and only seems to go lower as the window size increases. at a window size of 9, the loss is .0817. at a test window of 5, we get a loss of .0764. at a window of 4, we get a loss of .0759. It seems that For the FNG model, the window of 4 seems to work the best to get the lowest loss

At a window size of 1, the stock price model has a loss of .0038. at a window size of 9, the loss goes up to .0269. at a window size of 2, we get a loss of .0057. seems a window size of 1 gets us the best predictions.