# CMPT732Final_Project_Pair_Trading

## First part： Traditional Statistical Method
### Requirement
I use jupyter notobook with updated Anacaonda environment in order to show result plots. All packages are installed through Anaconada Navigator or Anaconda command with pip install. 
python version: 3.7.3
spark version: 3.0.1
needed package: pysaprk, pyfolio, statsmodels, pandas, numpy

### Single pair trading
#### DataSource
15stock.csv
#### Strategy
pair_trading_stat_coint1-stock15-final.ipynb
#### Backtesting
pair_trading_becktesting.ipynb
#### backtesting dataset
retcsv.csv

### Multiple pairs trading
#### DataSource
15stock.csv
#### Ensemble strategy 
pair_trading_stat_coint1-stock15_multiple.ipynb
#### Backtesting
pair_trading_becktesting_multiple.ipynb
#### backtesting dataset
retcsv_{item}_{item}.csv -- {item} can varies from a to k

## Second part： Pair Trading with Reinforcement Learning
### Requirement
See requirement.txt for all the package to install
### Implementation
#### 1. Create virtual environment 
#### 2. After all the package is installed
#### 3. Run the python code:
```
python3 RunningScript.py
```
#### 4. Wait for almost 20 min to see the result
