# Stochastic-Stock-to-Flow-Model

A basic Ridge Regression model in Python that uses the Bitcoin stock-to-flow ratio, mining difficulty, and Google Trends score to predict the price of Bitcoin. Cal Poly Economics 2020 senior project. Credit to Katya Vasilaky for a majority of the base Ridge code. 

# Prerequisite local installations:
1) Jupyter (Anaconda recommended if you don't already have Jupyter)
2) Pytrends (pip3 install pytrends)
3) CoinMetrics API (pip3 install coinmetrics)

# Usage:
1) Read the acompanying paper first
2) Make sure that each section of the Jupyter Notebook finishes running, particularly the initial few where data is being collected 
3) Feel free to adjust the dates to reflect recent changes. There are comments in the notebook that indicate this as well. 
4) Make sure that you split the data so that you can predict on out-of-sample data. The file is currently set to predict on out-of-sample data for the month of January, 2021.
5) Ridge will give you a different result each time you run the file and predict on the data. That is what you get with machine learning!

# Misc:
This code is still pretty messy, but it runs. Feel free to fork it/make whatever changes you want to make it run better. I'm just a macro guy with an elementary ability to code. I might update it someday in the future. 

