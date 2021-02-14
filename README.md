# deep_learning

## Which model has a lower loss?

The notebook which used closing price for the feature set had a lower loss compared to the notebook which used the fear and greed index (6.16% vs. 12.2%). These results were using 10 epochs and a 10 day window.

## Which model tracks the actual values better over time?

The model using closing price for the feature set more closely resembles the actual closing prices, as shown in the plots below

### Price Predictor Using Closing Price

![](https://github.com/alexgwise/deep_learning/blob/main/close_price_feature_model.PNG)

### Price Predictor Using FNG

![](https://github.com/alexgwise/deep_learning/blob/main/fng_feature_model.PNG)
