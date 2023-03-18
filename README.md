## Financial Analysis (Part I): Technical Analysis

We started with setting up the environment. I used Jupyter-Lab and importing data as a csv file using Pandas library.
We explored the data, removed index and converted object Date into datetime. We get to know Series and make some simple
calculations and normalizing of data. Then we calculated some new columns, created some new columns and drop the columns we didn't need. We used the min, max, argmin, argmax annd mean functions. In the next tutorial we used matplotlib to create some visulaizations, we visualized the 'Close' value of the AAPL stock trough time. Then we created a horizontal bar chart that for a summer of 2020. Then we used pandas datareader (example of simple getting data through simple APIs) instead of importing data throught a csv. I used the get_data_stooq. I had problems with getting the data using get_data_yahoo. The problem that Python returned was string indices must be integers, and according to youtube comments it was a common mistake that need to be solved according to the instructor. In the next tutorial we calculated pct_change, log_return and standard deviation, simple moving average ter exponential moving average using the rolling function. Then we calculated the MACD and Stochastic oscillator. MACD is a lagging indicator when trading is on the crossover. In the last tutorial we exported calculations in Excel sheets.

## Python for Finance (Part II): Risk and Return
This tutorial focuses on risk and return part of financial analysis.
