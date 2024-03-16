# Stock-Purchase-Recommender
A highly scalable stock purchase recommender (given specific tickers)

# Approaach
- Fetch 5 year data for selected tickers from yahoo finance API.
- Perform feature selection/expansion by evaluating the impact of different features on a stocks closing price on a specific date.
- Initiate spark cluster and create spark dataframes for the chosen tickers.
- Use LSTM's to fetch feature data for a future date
- Use regression model to predict the closing price.
- Order the tickers based on closing price. 
