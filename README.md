# healthdata-analysis

import pandas as pd
import xlrd
import numpy as np 
import matplotlib
import matplotlib.pylab as plt
from sklearn.decomposition import PCA
from sklearn import linear_model
from pandas.tools.plotting import scatter_matrix
import seaborn as sns
import codecs
import csv
from scipy import stats
import     statsmodels.api as sm
from sklearn.linear_model import LassoCV, LassoLarsCV, LassoLarsIC

from pandas.tools.plotting import scatter_matrix
from pandas.tools.plotting import lag_plot
from pandas.tools.plotting import autocorrelation_plot
from math import sqrt
from sklearn.metrics import mean_squared_error

