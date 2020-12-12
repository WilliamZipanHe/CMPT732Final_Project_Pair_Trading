# CMPT732Final_Project_Pair_Trading

## First part： Traditional Statistical Method
### Requirement
jupyter notobook with updated Anacaonda environment. packages are installed through Anaconada Navigator or Anaconda command with pip install
python 3.7
spark 3.0.1
needed package: pysaprk, pyfolio, statsmodels, pandas, numpy

### single pair trading
####DataSource
15stock.csv
####Strategy
pair_trading_stat_coint1-stock15.ipynb
####Backtesting
pair_trading_becktesting.ipynb
backtesting dataset: retcsv.csv

## multiple pairs trading
####DataSource
15stock.csv
####Ensemble strategy 
pair_trading_stat_coint1-stock15_multiple.ipynb
####Backtesting
pair_trading_becktesting_multiple.ipynb
retcsv_{item}_{item}.csv -- {item} can varies from a to k

## Second part： Pair Trading with Reinforcement Learning

