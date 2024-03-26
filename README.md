# Futures trend following with custom args

This trading strategy is designed for the [Quantiacs](https://quantiacs.com/contest) platform, which hosts competitions for trading algorithms. Detailed information about the competitions is available on the [official Quantiacs website](https://quantiacs.com/contest).

## How to Run the Strategy

### In an Online Environment

The strategy can be executed in an online environment using Jupiter or JupiterLab on the [Quantiacs personal dashboard](https://quantiacs.com/personalpage/homepage). To do this, clone the template in your personal account.

### In a Local Environment

To run the strategy locally, you need to install the [Quantiacs Toolbox](https://github.com/quantiacs/toolbox).

## Strategy Overview

This Jupyter notebook, titled **"strategy.ipynb,"** presents a sophisticated approach to **trend following** in the **futures market** with customizable arguments. It leverages a variety of Python libraries such as **xarray, numpy, pandas,** and **Plotly,** along with specific **quantiacs (qnt)** modules for data loading, technical analysis, statistical evaluation, graph plotting, and backtesting.

The notebook begins by importing essential libraries and loading data for **75 global derivatives** across **currencies, indices, bonds, energy,** and **metals** from leading futures exchanges. It details the process of downloading **20 years of data** using `qndata.futures.load_data`, visualizing historical trends, and implementing a **weight allocation strategy** based on **weighted moving averages (WMA)** and **rate of change (ROC)** as trend indicators.

Further, it introduces a function to calculate positions for multiple instruments with different parameters, showcasing the flexibility in strategy testing across various assets. The document proceeds with a **multi-pass backtesting approach,** ensuring rigorous validation of the strategy without forward-looking bias.

Ideal for **quant developers** and **traders,** this notebook combines data analysis, technical indicators, and backtesting to form a comprehensive futures trading strategy, emphasizing **trend following** with adjustable parameters for tailored strategy optimization.
