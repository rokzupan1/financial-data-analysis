## Financial Analysis (Part I): Technical Analysis

We started with setting up the environment. I used Jupyter-Lab and imported data as a csv file using Pandas library.
We explored the data, removed index and converted object Date into datetime. We get to know Series and make some simple
calculations and normalizing of data. Then we calculated some new columns, created some new columns and drop the columns we didn't need. We used the min, max, argmin, argmax annd mean functions. In the next tutorial we used matplotlib to create some visulaizations, we visualized the 'Close' value of the AAPL stock trough time. Then we created a horizontal bar chart that for a summer of 2020. Then we used pandas datareader (example of simple getting data through simple APIs) instead of importing data throught a csv. I used the get_data_stooq. I had problems with getting the data using get_data_yahoo. The problem that Python returned was string indices must be integers, and according to youtube comments it was a common mistake that need to be solved according to the instructor. In the next tutorial we calculated pct_change, log_return and standard deviation, simple moving average ter exponential moving average using the rolling function. Then we calculated the MACD and Stochastic oscillator. MACD is a lagging indicator when trading is on the crossover. In the last tutorial we exported calculations in Excel sheets.

## Python for Finance (Part II): Risk and Return
This tutorial focuses on risk and return part of financial analysis. We started by import libraries: numpy, pandas_datareader, datetime and pandas. We got the data using the APIs, specifically using pandas_datareader function get_data_stooq. We turned around the date so it was sorted from starting date in the first row to the ending date in the last column. I checked the data types and the type of variable the data was saved in. It was a dataframe. Then I changed the dataframe to numpy and check the shape of the data. Then we created some calculations like getting the logaritem of the values. Then we calculated portfolios of our stocks. We defined the ratio of each stock in our portoflio and how much we gained or lose through the specific time frame when we observe the 3 stocks. AAPL, MSFT, IBM. In the second tutorial we calculated volatility. We defined that volatility has a number of different meanings. One interpretation is that it is equivalent as risk. We calculated the average_true_range and plotted it with data closing price on the same visualization. We can than see how theese two values are correlated. In the third tutorial we calculated the risk free return and standard deviation of porfolio (or the risk). We plotted the histogram of the logartimic return of the portfolio and then we calculated the sharpe ratio of the portfolio. Then we continue to Monte Carlo Simulation tutorial. The Monte Carlo simulation is a mathematical technique that predicts possible outcomes of an uncertain event. First part is introduction to Monte Carlo simulatiion, then we did the Monte Carlo Simulation with Portfolios and Sharpe Ratio. We needed pandas, matplot, datetime and pandas_datareader. We got the data using the get_data_stooq and then use only the close values of the stock. We calculated the log returns and created a random weight of the portfolio of the 4 stocks. We calculated the expected return and expected volatility and then the sharpe ratio. Then we did the monte carlo simulation where we defined weights, exp_rtns, exp_vols and sharpe_ratios. We wanted to get the best sharpe ratio of the sharpe ratios calculation. We then checked the portfolio of the best sharpe ratio and created a plot that plots Expected Return on Expected Volatility. Next tutorial was about correlation between stocks and S&P 500. After that we learned about linear regression - which attempts how X causes Y. We continued by calculating Beta Calculaation with Python for several stocks. We finished our second tutorial by calculatin Capital Asset Pricing Model (CAPM).

