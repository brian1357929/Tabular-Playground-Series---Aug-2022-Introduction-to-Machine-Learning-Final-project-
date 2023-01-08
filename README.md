# Tabular Playground Series - Aug 2022 (Introduction to Machine Learning Final project)
**This code  refer(https://www.kaggle.com/code/rsizem2/tps-08-22-hyperparameter-search)**

## 1. Specification of dependencies
this code is test on google colab. It have most library on it.
but some package may need to install yourself.

```
!pip install category-encoders
!pip install optuna
```
    
## 2. Training and Evaluation
train.ipynb use xgboost with hyperparameter search. Divide train data to 5-fold to test hyperparameter. Having best hyperparameter then use it to train 10 model for these 5 fold then save them as model**i**.pickle.   

inference.ipynb can load  these model. Final prediction would be the average predict of these model. inference.ipynb would output the result as submission.
