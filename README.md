# Implementation and Evaluation of Binary Classification Models

## Goals

* Implement, optimize and compare different classification models.
* Investiate and analyse interesting datasets of various sizes and complexity.

## Datasets

Dataset                 | Instances  | Features | Type                | Missing Values | Remarks | Links
----------------------- | ---------- | -------- | ------------------- | -------------- | ------- | -----
Wisconsin Breast Cancer |        569 | 30       | continuous numeric  | no             | *clean* dataset, no need for feature engineering, great for implementing and optimizing different classifiers | [UCI page](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29), [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
Pima Indian Diabetes    |        768 |  8       | continuous numeric  | yes (indicated by 0)             | --      | [UCI page](https://web.archive.org/web/20180303223954/https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes), [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
Mushroom                |      8,124 | 22       | categorial          | yes            | -- | [UCI page](https://archive.ics.uci.edu/ml/datasets/Mushroom), [Kaggle](https://www.kaggle.com/uciml/mushroom-classification)
Adult Census Income     |     48,842 | 14       | categorial, integer | yes            | -- | [UCI page](https://archive.ics.uci.edu/ml/datasets/Census+Income), [Kaggle](https://www.kaggle.com/uciml/adult-census-income)
Higgs                   | 11,000,000 | 28       | real                | N/A            | -- | [UCI page](https://archive.ics.uci.edu/ml/datasets/HIGGS), [Kaggle](https://www.kaggle.com/c/higgs-boson/data)
