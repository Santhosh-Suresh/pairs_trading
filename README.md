# pairs_trading

This is the Capstone project for Group 2843 for the WQU MSc FE 690 course Mar 23 term. Also, this project is an implementation of a pair trading strategy. Pair trading is a statistical arbitrage trading strategy that seeks to take advantage of the correlation between two assets by simultaneously buying one asset and selling the other asset. The objective of this project is to identify pairs of stocks that have a high correlation and then use them to generate profits through trading.

## Requirements
To run this project, you will need the following:

Python 3.6 or later
Pandas
NumPy
Matplotlib
Scikit-Learn

## Getting Started

To get started, clone this repository to your local machine:

```
git clone https://github.com/your-username/pairs_trading.git
```
Change into the project directory:

```
cd pairs_trading
```

Install the required packages:

```
pip install -r requirements.txt
```

Run the pair trading strategy:

```
python pair_trading_strategy.py
```

This will generate a plot of the profit and loss over time.

## Usage
The pair trading strategy is implemented in the pair_trading_strategy.py file. The code reads in a CSV file containing historical data for two stocks and performs the following steps:

Compute the rolling mean and standard deviation of the difference in price between the two stocks.
Compute the z-score of the difference in price between the two stocks.
Enter a long or short position in the stocks based on the z-score.
You can modify the parameters of the strategy by editing the variables at the top of the pair_trading_strategy.py file.

## Data
The data used in this project is historical stock price data obtained from Yahoo Finance. The data is stored in CSV format in the data directory.

## Results

The results of the pair trading strategy are shown in the results directory. This directory contains plots of the profit and loss over time for each pair of stocks.

## License
This project is licensed under the GNU GPL v3 License. See the LICENSE file for more information.
