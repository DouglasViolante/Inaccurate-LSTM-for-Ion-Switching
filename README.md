# Inaccurate LSTM Architecture for Ion Switching Open Channels Counting


A python low accuracy try on a [Kaggle](kaggle.com) competition with dataset provided by *University of London*, with the main objective of counting the number of channels open at a given time point in a data backed by a biological context.

The data is a time-series, where the Y-axis is the Current (pA) and the X-axis is the Time (seconds).

The Competition page, details and data can be found [here](https://www.kaggle.com/c/liverpool-ion-switching)

![Model Summary](/ModelSummary.png)

As seen in the above image, the small LSTM architecture developed, was inacurate in counting the number of channels that were open in a given time point, because the accuracy reached in comparison with validation-data was **less than 25%**, due to that the test-data was not used.

With the personal interest of understand LSTMs and GRUs.


