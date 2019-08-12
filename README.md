# stock-prediction
This jupyter notebook illustrates three strategies used to make trading decisions for auto manufacturer symbols and mobile provider symbols separately. Examiend strategies include a moving average crossover trading strategy, as well as trading based on predicted probabilities produced by training a neural network on historical data and a buy and hold strategy. Stock data is scraped in the script using the pandas data reader module.

## Moving Average Crossover Strategy
Returns are visualized from trading on days when the fast moving average crosses over the slow moving average.

## Buy and Hold SPY
Returns are visualized from the simpler strategy of buying and holding each given stock against the SPY symbol which is representative of the market as a whole.

## Trading decisions based on Neural Network predictions
The CNTK module is used to train a neural network on stock data. We make trading decisions based on predictions from this neural network and compare them against the returns from the other strategies.
