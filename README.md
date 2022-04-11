# Bootcamp_Week_3

# Crypto Arbitrage Analysis

This program is designed to analyze the arbitrage opportunties that may or may not exist with trading Bitcoin between multiple exchanges, in this case Bitstamp and Coinbase. Initially the program takes in the data frames with the starting data, by default in the dual .csv files within the resources sub-folder. Next we take some intiail steps to prepare and clean the data to ensure future analysis is free of errors that might skew our analysis. To begin parsing the data, the program does overall summaries of the two different exchanges and their closing prices for bitcoin. As an intial analysis, the program then overlays the two data frames together in visual plots to allow for quick high level intepretation of the underlying question of arbitrage opportunity. Finally, we go granular to break down profit potential on specific dates and then take these findings and summarize our findings for easy reference for any interested parties.

For additional reference, bitstamp.csv covers the January through March window of 2018 for the bitstamp exchange, while coinbase.csv covers the same January through March 2018 window except this time for the coinbase exchange. 

---

## Technologies

Within this program, we will make use of the following external python modules:
  -- pandas
  -- matplotlib
  -- Pathlib
  
  Additionally, this program was created within a python v3.7 build, and its relevant dependencies.

---

## Installation Guide

To utilize this program, within your terminal you will have to install the required libraries. Within your terminal, input the following commands:

```python
pip install pandas
```

```python
pip install matplotlib
```

```python
pip install pathlib
```

At the beginning the *crypto_arbitrage.ipynb* file the technologies are calling in with this code:

import pandas as pd
from pathlib import Path
%matplotlib inline

---

## Usage

To operate this program, open up your terminal of choice and navigate to the directory in which you have downloaded the files within this repository. Open Jupyter Lab with the command: 

```python
jupyter lab
```  

This should open jupyter lab to the filepath in which you have the repo file, and you simply need double click the *crypto_arbitrage.ipynb* file to open it. Upon opening, select the menu button with two right facing arrows at the top of the notebook, which will run the entire file. It will ask you to confirm you wish to restart the file, to which you will confirm. Wait a few moments for the program to operate as intended, and peruse the resulting data at your leisure. If you wish, simply skip to the end for my analysis of the preceding information. 

---

## Contributors

Colton Mayes ctmayes@gmail.com

---

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.
