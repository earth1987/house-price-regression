# House price prediction

The goal is to develop regression models to predict house prices based on their characteristics. 

**Why?**

Predicting house prices with machine learning offers benefits such as aiding real estate investment decisions, helping buyers and sellers make informed choices, assessing lending risks, analyzing market trends, and automating valuation processes.

## Scope

The available data describes house sold in King County, USA from May 2014 to May 2015. It has been downloaded from [Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data). Two multiple linear regression algorithms will be tested, ordinary least squares and lasso regression. These will not be used to extrapolate beyond the range of the available data. Instead predictions will be made for a randomly sampled holdout test set.

## File structure

<pre>
|- notebooks/
   |- data_exploration.ipynb
   |- linear_model_selection_evaluation.ipynb
   |- nonlinear_model_selection_evaluation.ipynb
   |- figures/
|- house-price-regression/
   |- custom_funcs.py
   |- config.py
|- data/
   |- raw/
   |- cleaned/
|- README.md
</pre>



