# Project_2

Our project is broken down into three parts:

Part 1:
Using Alpaca Api, we pulled 3 years worth of data for SPY. We utilized the 'Open, High, Low, Close, Volume and Actual' data columns. From this, we each used a different indicator(Exponential Moving Average, Ease of Movement, Triple Exponential Moving Average, and the Hull Moving Average)from Finta library to create Long and Short trade signal.

Part 2:
Consisted of us using that same signals dataframe to train and test our data. We all utilized the SVC classifier model from SKlearn to establish a base model when comparing to the different classifiers used from SKlearn(Decision Tree, Logistic RegressionCV, Stochastic Gradient Descent, Calibrated ClassifierCV)

Part 3:
Consisted of us evaluating the following for the baseline strategy versus our own individual strategies; 'Annualized Return, Cumulative Returns, Annual Volatility, Sharpe Ratio'.