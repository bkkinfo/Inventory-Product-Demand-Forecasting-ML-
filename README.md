## Inventory Forecasting using Machine Learning
### Inventory forecasting is the process of making estimations about future customer demand over a defined period, using historical data as well as demand drivers to better food production and supply needs.

Usually organisations follow tranditional forecasting techniques/algorithms such as Auto Arima, Auto Arima, Sarima, Simple moving average and many more.


## Table of Contents
Goal
Workflow
Required Packages
Goal
Due to the recent boost in AI world, companies have started researching the possibility of using machine learning in place of tranditional approach.

Tuning traditional algorithms takes a significant amount of efforts and domain expertise as well.

In this repo, we are trying to figure out a way of predict the same using machine learning algorithms.

## Data
The dataset comprised of units sold on a daily basis along with details regarding the sales, eg. SKU(product id), Store, price etc.

record_ID, week, store_id, sku_id, total_price, base_price, is_featured_sku, is_display_sku, units_sold

## Workflow
```bash
Handling missing values
Feature selection
Converting dataset into time series format to apply supervised learning approach.
Regression Modeling
Random Forest
XGBoost
SVM (future scope)
Hyperparameter Tuning
Result
```

### Required Packages
```bash
numpy
pandas
sklearn
easypreprocessing
seaborn
matplotlib
xgboost
```
