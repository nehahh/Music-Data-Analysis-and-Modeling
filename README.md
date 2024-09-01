# Music-Data-Analysis-and-Modeling

This repository contains a Jupyter notebook that demonstrates data analysis and modeling on a music dataset. The notebook includes steps for data cleaning, exploratory data analysis, clustering, and regression.

## Table of Contents

1. [Import Data & Packages](#import-data--packages)
2. [Clean Data](#clean-data)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Clustering](#clustering)
5. [Regression](#regression)

## Import Data & Packages

The notebook starts by importing necessary packages and loading the dataset. The dataset is read from a CSV file and basic information is displayed.

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import warnings
warnings.filterwarnings('ignore')
