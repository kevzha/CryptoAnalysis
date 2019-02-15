# CryptoAnalysis

#importing the required tools

#alpha vantage tools
!pip install alpha_vantage
import alpha_vantage
%matplotlib inline
from alpha_vantage.timeseries import TimeSeries
from alpha_vantage.cryptocurrencies import CryptoCurrencies

#dataframe and calculations libraries
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns