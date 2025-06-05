# Superiority of Neural Networks for Trading Volume Forecasts of Stocks and Cryptocurrencies

Trading volume is an important variable for successfully capturing market risks along with asset price/returns. Recently, there has been a growing interest in deep learning methods to forecast the trading volume of stocks using historical volatility as a feature. Unlike the existing work, this study proposes a novel data-driven log volatility forecast as an extra feature to improve trading volume forecasts.

The PDF copy of the paper can be downloaded from here: [Download Paper](https://ieeexplore.ieee.org/abstract/document/10371869) 

A preprint version of the paper is available in the repository

Programming Language: [R](https://cran.r-project.org/bin/windows/base/) / [RStudio](https://posit.co/downloads/)

Data: The provided R codes download data directly from [Yahoo!Finance](https://ca.finance.yahoo.com/)

### Findings

The trading volume forecasts play a crucial role in measuring the substantial influence of price movements on stocks and cryptocurrencies. In this study, the driving idea, unlike the existing work, is demonstrating the superiority of the trading volume forecasts using the `nnetar` function from the `forecast` package in R over the neural networks using `keras` and `tensorflow` packages. Moreover, this paper considers the extra features, such as data-driven log volatility forecasts and log returns, to improve trading volume forecasts. The experimental results show that trading volume forecasts using the `nnetar` network are superior to the `keras` neural network forecasts.
