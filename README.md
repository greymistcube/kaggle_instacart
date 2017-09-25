# Instacart Customer Reorder Prediction
* This is my attempt at [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis/)
  competition hosted by [Kaggle](https://www.kaggle.com/).
* Detailed description of the competition and its goal can be found in the link
  above.

## 01. Data Integrity Check
* Check to see if there are any possible missing values and mismatch between
  the datasets as the dataset is spread accross multiple files in different
  formats.

## 02. Exploratory Data Analysis
* Gain some insight into the given dataset.

## 03. Prediction
* A binary decision tree model (BDT) is used.
* The goal here was *not* to get the highest possible score, but to use a small
  number of features with a fast computing model and get a score that is
  reasonably close to the score attained by a more robust gradient boosting
  method (in particular, XGBoost).
* Compared to the base XGBoost model used by most participants, which gives
  the score of 0.38 after several hours of computation, it was possible to
  attain a score of 0.37 under a minute with BDT.