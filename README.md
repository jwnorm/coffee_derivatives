## Thesis - The Coffee Derivatives Market
Author: Jacob Norman  
Date: 04.10.2019

This is my thesis for my undergrad at Oakland University in 2019. It concerns analyzing
the spot, futures, and option markets for Arabica green coffee beans.  

The goal was to forecast the price movement of the commodity for roughly a two year 
time horizon. I used an ensemble of ARIMA and GARCH models to create my predictions, 
which was done completely in R.

### Files:

- **corplot.jpg** - correlation image output
- **futures_model.html** - html output of futures_model.Rmd; created with knitr
- **futures_model.Rmd** - analysis of futures prices
- **optimal_hedge_ratio.html** - html output of optimal_hedge_ratio.Rmd; created with knitr
- **optimal_hedge_ratio.Rmd** - analysis of the optimal hedge ratio and correlation between
spot and futures prices
- **spot.jpg** - spot model image output
- **spot_model.html** - html output of spot_model.Rmd; created with knitr
- **spot_model.Rmd** - analysis of spot prices
- **spot_model-log.Rmd** - analysis of log of spot prices
- **spot-log.jpg** - spot model using log of price image output
- **thesis.Rproj** - R project file