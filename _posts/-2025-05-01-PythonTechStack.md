---
layout: post
title: Python Tech Stack
---



### Data Processing 
  - In Memory: [polars](https://github.com/pola-rs/polars)
  - Big Data: [spark](https://github.com/apache/spark)
  - Data Stream: [kafka](https://kafka.apache.org/)

### Data visualization
  - [plotly](https://github.com/plotly/plotly.py)
  - [dash](https://github.com/plotly/dash)
  - [streamlit](https://github.com/streamlit/streamlit)
   
### Web Development 
  - [django](https://github.com/django/django)
  - [selenium](https://github.com/SeleniumHQ/selenium)

### Statistical Models 
  - [scikit-learn](https://github.com/scikit-learn/scikit-learn)
  - [statsmodels](https://github.com/statsmodels/statsmodels)
  - [polars-ds](https://github.com/abstractqqq/polars_ds_extension)
  - [polars-ols](https://github.com/azmyrajab/polars_ols)
  - [cuml](https://github.com/rapidsai/cuml)

Work to do: Reimplement scikit-learn and stats models in polars/Rust 
Work to do: Efficient batch model fitting for out-of-memory data of common statistical models, such as ridge regression. 


### Time Series 
  - [tsfresh](https://github.com/blue-yonder/tsfresh)
  - [darts](https://github.com/unit8co/darts)

Work to do: Feature Expansion for time series in polars/Rust 


### Gradient Boosting Decision Trees
  - [XGBoost](https://github.com/dmlc/xgboost)
  - [LightGBM](https://github.com/microsoft/LightGBM)
  - [CatBoost](https://github.com/catboost/catboost)
  - [NGBoost](https://github.com/stanfordmlgroup/ngboost)
  - Unpublished work from my PhD Research on multi-level GBDT with regime regularisation. 

### Deep Learning 
  - [PyTorch](https://github.com/pytorch/pytorch)
  - [PyTorch-lightning](https://github.com/Lightning-AI/pytorch-lightning)
  - [Jax](https://github.com/jax-ml/jax)

Work to do: integrate the above with polars so that a simple MLP can be trained as polars functions/expressions 

### Reinforcement Learning 
  - [Ray-RLlib](https://docs.ray.io/en/latest/rllib/index.html)
  - [stable-baselines](https://github.com/DLR-RM/stable-baselines3)
  - [gym](https://github.com/openai/gym)

### Hyperparameter optimisation 
  - Single Machine: [optuna](https://github.com/optuna/optuna)
  - Multiple Machines: [Ray](https://docs.ray.io/en/latest/tune/index.html)

### Distributed Programming 
  - [joblib](https://github.com/joblib/joblib)
  - [dask](https://github.com/dask/dask)

### Natural Language Processing 
  - [Transformer](https://github.com/huggingface/transformers)
  - [Spacy](https://github.com/explosion/spaCy)

### Genetic Algorithms 

Feature expansion of Time Series 
