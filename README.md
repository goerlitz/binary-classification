# Implementation and Evaluation of Binary Classification Models

## Goals

* Implement, optimize and compare different classification models.
* Investiate and analyse interesting datasets of various sizes and complexity.

## Datasets

Dataset                 | Instances  | Features | Type                | Missing Values | Remarks | Links
----------------------- | ---------- | -------- | ------------------- | -------------- | ------- | -----
Wisconsin Breast Cancer |        569 | 30       | continuous numeric  | no             | *clean* dataset, no need for feature engineering, great for implementing and optimizing different classifiers, **included in Scikit-Learn** | [UCI](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29), [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data), [OpenML](https://www.openml.org/d/1510)
Pima Indian Diabetes    |        768 |  8       | continuous numeric  | yes (indicated by 0)             | --      | [UCI](https://web.archive.org/web/20180303223954/https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes), [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database), [OpenML](https://www.openml.org/d/37)
Mushroom                |      8,124 | 22       | categorial          | yes            | -- | [UCI](https://archive.ics.uci.edu/ml/datasets/Mushroom), [Kaggle](https://www.kaggle.com/uciml/mushroom-classification), [OpenML](https://www.openml.org/d/24)
Adult / Census Income   |     48,842 | 14       | categorial, integer | yes            | -- | [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income), [Kaggle](https://www.kaggle.com/uciml/adult-census-income), [OpenML](https://www.openml.org/d/1590)
Higgs                   | 11,000,000 | 28       | real                | N/A            | -- | [UCI](https://archive.ics.uci.edu/ml/datasets/HIGGS), [Kaggle](https://www.kaggle.com/c/higgs-boson/data)
Shuttle statlog         |     58,000 |  8       | numeric             | --             | Imbalanced **Multi-class** (80% class 1) | [UCI](https://archive.ics.uci.edu/ml/datasets/Statlog+%28Shuttle%29), [OpenML](https://www.openml.org/d/40685)
