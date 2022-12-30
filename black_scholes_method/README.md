# black_scholes_method
The Black-Scholes formula is a mathematical model used to price European-style options. It is a widely used tool in finance and is named after Fischer Black and Myron Scholes, who developed it in 1973. European-style options can only be exercised at the expiration date of the option, while American-style options can be exercised at any time before the expiration date.


The Black-Scholes formula takes into account five main factors: the stock price, the option's strike price, the time until the option's expiration date, the risk-free interest rate, and the option's implied volatility. The formula allows the option's price to be calculated based on these factors and the option's type (call or put). A call option gives the holder the right to buy the underlying stock at a predetermined price (the strike price), while a put option gives the holder the right to sell the underlying stock at a predetermined price.


The Black-Scholes formula is commonly used to value options on stocks, but it can also be used to value options on other assets such as currencies, commodities, and bonds. It is important to note that the Black-Scholes formula makes several assumptions, including that the stock price follows a lognormal distribution, that the risk-free interest rate is constant, and that there are no dividends paid out on the stock. These assumptions may not always hold true in practice, so the Black-Scholes formula may not always accurately price options.


In this project, I have implemented the black-scholes formula and tested out utilizing real world options. Further, I assessed when the model can be implemented and some limitations. I have generated the overarching function and have illustrated what parameters must be inputted. 
