# LGBMRegressor
## Overview
A simple implementation to regression problems using Python 2.7 and LightGBM. [LGBMRegressor](https://github.com/albertkklam/LGBMRegressor/blob/master/LGBMRegressor.ipynb) is a general purpose script for model training using LightGBM. It contains:

* Functions to preprocess a data file into the necessary train and test set Datasets for LightGBM
* Functions to convert categorical variables into dense vectors
* Additional user functionality that allows notification updates to be sent to a user's chosen Slack channel, so that you know when your model has finished training
* Implementation of the DART algorithm
* Implementation of early stopping cross-validation to find the best tree

## Installing LightGBM for Python
Follow instructions [here](https://github.com/Microsoft/LightGBM/tree/master/python-package)

## Resources
Here are some additional resources if you are looking to explore LightGBM more extensively:

1. [LightGBM Features](https://github.com/Microsoft/LightGBM/wiki/Features)
2. [LightGBM's Python API](https://github.com/Microsoft/LightGBM/blob/master/docs/Python-API.md)
3. [LightGBM's complete parameter specification](https://github.com/Microsoft/LightGBM/blob/master/docs/Parameters.md)
4. [DART: Dropouts meet Multiple Additive Regression Trees](https://arxiv.org/pdf/1505.01866.pdf)
5. [Optimisation in network communication](http://wwwi10.lrr.in.tum.de/~gerndt/home/Teaching/HPCSeminar/mpich_multi_coll.pdf)
6. [Voting parallel learning](http://papers.nips.cc/paper/6381-a-communication-efficient-parallel-algorithm-for-decision-tree)
7. [Fair loss](https://www.kaggle.com/c/allstate-claims-severity/discussion/24520)

LightGBM is a relatively new GBM framework. If you are looking to learn more about GBMs in general, here are some additional resources about XGBoost, which has more extensive documentation and is configured very similarly to LightGBM:

1. [XGBRegressor](https://github.com/albertkklam/XGBRegressor) is a general purpose script for model training using XGBoost
2. [Introduction to Boosted Trees and the XGBoost algorithm](http://xgboost.readthedocs.io/en/latest/model.html)
3. [The Python API documentation for XGBoost](http://xgboost.readthedocs.io/en/latest/python/python_api.html)
4. [Complete Guide to Parameter Tuning in XGBoost](https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/)
5. [Tong He's XGBoost presentation](https://www.slideshare.net/ShangxuanZhang/xgboost)
