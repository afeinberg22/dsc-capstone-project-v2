TWITTER SENTIMENT TO PREDICT STOCK PRICE

In this project, I test the correlation between twitter and stock price for Apple with the end goal aimed at creating a prediction model that can spit out a predicted change in stock price. My notebook is organized using the OSEMN process.

Using Twint, I was able to gather 1000 tweets dating from Jan 1 - Feb 28 2019. After gathering these tweets I then clean and run a sentiment analayis on them to determine which tweets are positive, negative and/or somewhere in between. Along the way I show visualizations on the types of words and meaning of tweet sentences in our data.

Using Yahoo finance I pull stock prices for Apple using the same dates as listed above. Ultimately I narrow this data into a single column that shows the change in price from when the market opened and closed that day. This demonstrates if the stock price was positive or negative.

Finally I combine these two data sets and run a multivariate time series model to predict stock prices given subjectviity.