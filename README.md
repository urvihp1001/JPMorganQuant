# JPMorganQuant
I wrote ML code for my job simulation as a Quant Researcher for JP Morgan on Forage.
## Assignment1
I studied concepts of Time Series Forecasting (SMA, ARIMA, SARIMAX, Seasonal decomposition, trends and so on) to predict the value of a commodity contract extrapolated over a year.
I also studied what a commodity contract is. Here, Natural gas is used as an example.
A Commodity Contract is an agreement between warehouse owners and members of supply-chain to store their oil/natural gas over a period of time- since commodities are only useful when we can store them
Injection and withdrawal are decided on inception of contract, as well as storage costs.
Eg. A firm buys oil at lower cost in summer (supply is higher) and sells at higher cost in winter (demand greater) - and therefore will require a place to store the oil.
So this assignment is a dataset of dates and prices, we are supposed to predict the prices of a particualr date on same day next year.
Linear regression being far too simple, Polyfit() was used so that the time is taken as x and a function of y (price) is made of that x
this was only initial.
The TSA part comes soon...
