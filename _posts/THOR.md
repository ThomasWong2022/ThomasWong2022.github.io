# THOR: Time-Varying High-dimensional Ordinal Regression 

THOR is a new autoML tool for temporal tabular datasets and time series. It handles high dimensional datasets with distribution shifts better than other tools. Inspired by the Numerai competiton, THOR has evolved from a specific tool for Numerai competition into a general ML pipeline which has many applications in finance and healthcare. 

In the following I list some features in THOR. It is not an exhausive list and there are more proprietary features that is not listed here. 

## GBDT2.0

A customisted LightGBM-based Gradient Boosting Decision Trees models for temporal tabular datasets. 


## DeepLearner2.0

A novel deep learning model for temporal tabular datasets, which complements well with the above GBDT-based models. 


## PortfolioOpt2.0

A new method to combine predictions from machine learning model using well-known theories from finance.
Using the best research results from **both** finance and reinfrocement learning, 
the method can maximise the portfolio return (or minimise the given loss function) within required risk metrics.


## TimeSeriesHybrid 

A new method which combines classical and machine learning techniques for feature engineering and sequence modelling. 
A hybrid approach which demonstrate robust performances for high dimensional time-series. 

## TrendFollower2.0 

An enhanced implmentation of trend following strategies with improved robustness and lower risks than the standard implmentation of moving averages. 


# Mjolnir 

Mjolnir is a closely connected autoML tool which transforms various ML problems into suitable formats so that can be used by THOR. 

  - Convert Classification problems into Regression problems 
  - Convert non-numerical features into ordinal ones
  - Convert low dimensional problems into high dimensional ones
  - Convert Static Datasets into Time Varying ones 

