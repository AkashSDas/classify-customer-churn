# classify-customer-churn

Here [CustomerChurnRate](https://www.kaggle.com/gangliu/customerchurnrate) dataset by [Gang Liu](https://www.kaggle.com/gangliu) is used classify whether a customer is going to churn or not. Using the dataset `EDA` is done.

**While doing this we'll**

- Deal with `outliers` using the `iqr` and `z-scores` methods
- Feature selection using `backward elimination`

## Table of contents

- [Getting started](#getting-started)
- [EDA](#eda)
- [License](#license)

## Getting started

The [notebook](https://www.kaggle.com/akashsdas/classify-customer-churn) is available on Kaggle to work in the same environment where this notebook was created i.e. use the same version packages used, etc...

## EDA

**Correlation matrix**

![](./docs/imgs/corr.png)

**Count plot (how unbalanced the dataset is)**

![](./docs/imgs/count_plot.png)

## Model performance

**Cross validation scores for different models**

![](./docs/imgs/score2.png)

**Learning curve**

![](./docs/imgs/learning-curve.png)

**Confusion matrix, without normalization**

![](./docs/imgs/confusion-matrix.png)

![](./docs/imgs/score1.png)

## License

[APACHE LICENSE, VERSION 2.0](./LICENSE)
