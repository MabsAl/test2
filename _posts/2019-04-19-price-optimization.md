---
layout: post
title: Price optimization: maximizing revenue/profit
---

### Problem statement
Setting a right price of products/services is one of the most important decisions a business can make. Under-pricing and over-pricing both can hurt a company’s bottom line. Two determinants/indicators of business revenue are product prices and quantity sold. At higher price revenue is expected to be higher, if quantity sold is constant. However we know from our everyday experience that price and quantity are inversely related – as the price of something goes up, people have less tendency to buy it.

The opposite is also true, that is, as price goes down, sales go up (that’s why we big “sale” events in shopping malls round the year). But that doesn’t mean that the revenue will always go up.

So the big question is: if higher price means sales down and at lower price revenue goes down then where is the sweet spot, the right price, that maximizes revenue ?

So ?

With a simple example let’s examine how to optimization price to maximize revenue/profit.

`Import libraries
from __future__ import print_function
import numpy as np
import pandas as pd
from pandas import DataFrame
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
from statsmodels.compat import lzip
from statsmodels.formula.api import ols
%matplotlib inline`
