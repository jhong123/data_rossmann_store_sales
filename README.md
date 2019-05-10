专门给 colab 使用的竞赛数据，数据源来自 kaggle。

colab ：

[https://colab.research.google.com](https://colab.research.google.com/)



# 使用方法

登录 colab，加载数据即可使用：

!git clone git@github.com:jhong123/data_rossmann_store_sales.git



# kaggle 竞赛数据

https://www.kaggle.com/c/rossmann-store-sales/overview



# Data Description

You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

### Files

- **train.csv** - historical data including Sales
- **test.csv** - historical data excluding Sales
- **sample_submission.csv** - a sample submission file in the correct format
- **store.csv** - supplemental information about the stores

### Data fields

Most of the fields are self-explanatory. The following are descriptions for those that aren't.

- **Id** - an Id that represents a (Store, Date) duple within the test set
- **Store** - a unique Id for each store
- **Sales** - the turnover for any given day (this is what you are predicting)

