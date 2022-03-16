# Time & Seasonality Features in Time Series

Time and seasonality features are often assumed in time series analysis, ignoring their crucial role as an input in model calibration. Finding the optimal form of seasonality effects should be part of the model-building process, and not simply taken for granted, especially for phenomenon that are outside of the natural world.

The study investigates the comparative performance of utilizing sine and cosine cyclic seasonality features for hour and month, versus using seasonality dummy and numeric variables. Six popular machine learning models are evaluated in terms of their performance with regards to the various seasonality features, namely Lasso Regression, Ridge Regression, Random Forest, Xtreme Gradient Boost, Support Vector Machine and Multi-Layer Perceptron. 

The conclusion of the study is that we should be data-focused, and not assume that any particular time/seasonality feature choice is always optimal, unless there is solid domain knowledge indicating a particular choice. Nonetheless, there are certain rules of thumb if one needs to undertake a quick-and-dirty initial analysis. Tree-based models tend to perform well with numeric seasonality features. Linear models meanwhile tend to perform well with dummy seasonality variables.

These files contain the data and Python code used for the article published in: https://towardsdatascience.com/time-seasonality-features-in-time-series-7e8236f7b04a?sk=4b3d3f6c4056d12ba002fab887b55400
