# Temporal-Attention-time-series-analysis
A Temporal Attention augmented Bilinear Network for Directional Prediction of Financial Time Series

A bilinear network with temporal attention proposed by Dat Thanh Tran, Alexandros Iosifidis, Juho Kanniainen, and Moncef Gabbouj 
in their insightful paper:

[Temporal Attention-Augmented Bilinear Network for Financial Time-Series Data Analysis](https://ieeexplore.ieee.org/document/8476227)

This work presents my modification of their original program ([which can be found here](https://github.com/viebboy/TABL)) to work with daily stock data as opposed to limit order book information they use in their paper.

A number of features are generated for the stock including RSI, Bollinger Bands, Moving-Average with Variable Period, ROC, ATR, Weighted Moving-Average, Daily VIX, Hilbert-Transform Trendmode, and ARIMA forecast. This is by no means an exhaustive list of features, many more can be added to the model (rolling percentile GDP, payroll, Unemployment, etc) as the network topology will automatically update to the appropriate dimension. 

The proposed model produces 95% accuracy in direction prediction of the asset (AAPL) out of sample.
