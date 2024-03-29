# Robo-Advising

!! Second place winner for low-risk portfolio generation

## Introduction
Our team chose to build a safe portfolio, which means we wanted the total portfolio value to experience very minimal change from the starting value of 500,000 dollars between the start date and the end date. 

We chose to have the maximum number of stocks allowed in our portfolio. This was because we want to have our portfolio as diversified as possible, in order to mitigate non-systematic risk such as business risk, financial risk and default risk. 
Through diversification, investors are able to reduce the non-market risk, but they are unable to reduce the systematic risk. This means having an inter-industry portfolio with the least correlated stocks from different industries. This is to neutralize the negative performance of an individual stock on the total portfolio value.

## Our Strategy
In order to pick 25 stocks to build our safe portfolio, we want to be able to quantify and measure the risk of our total portfolio to ensure it is as safe as possible. The three measures we used are beta, which is a measurement of systematic risk, standard deviation, which is a measurement of the total risk of our portfolio’s expected return, and correlation, which is a measurement of how closely the returns of each security are related to each other.

The following is a summary of the strategy we implemented:

  1. Filter the Stocks
  2. Calculate Beta
  3. Calculate Standard Deviation
  4. Rankings
  5. Calculate Correlation
  6. Portfolio Weightings
  7. Generate Final Portfolio

