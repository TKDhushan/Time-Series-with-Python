# Time-Series-with-Python
- 本项目完整描述了用ARMA和Garch模型进行股票收益率时间序列分析的完整过程，并尽量详细地对代码进行了说明，注释包括中文和英文版本
- This project describes the complete process of stock return time series analysis using ARMA and Garch models, and explains the code in as much detail as possible. The notes include Chinese and English versions.
- TS_1是对数据的预处理，包括平稳性检验（ADF检验），白噪音检验（LB检验），自相关图（ACF）和偏自相关图（PACF）
- TS_1 is the preprocessing of the data, including stationary test (ADF test), white noise test (LB test), autocorrelation plot (ACF) and partial autocorrelation plot (PACF).
- TS_2是拟合ARMA模型，并对残差做白噪音检验，作图
- TS_2 is a fitted ARMA model, and a white noise test is performed on the residuals to make a map.
- TS_3是对ARMA模型的残差拟合GARCH模型，并画出波动率的图，进行波动率预测
- TS_3 is a GARCH model that fits the residuals of the ARMA model, and plots the volatility to predict the volatility.
