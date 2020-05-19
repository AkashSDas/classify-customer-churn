

# Customer Churn

  

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

  
  

## Table of contents

  

*  [About](#about)

* [Technologies Used](#technologies-used)

* [Results of the Project](#results-of-the-project)

*  [Installation](#installation)

*  [License](#license)

  
  

## About

> For any company it is very important that they retain their customers. So knowing if what are the reasons that can lead a customer to leave their services.

> Using `Data Science` and `Machine Learning` to build a system that can predict whether a customer will leave their services or not.

> Since having an `imbalanced` using `SMOTE` algorithm to  `balance` the dataset so that we don't have a biased result.

> Using `feature selection` to select relevant features that affect whether a customer will churn or not.

> Using `cross validation` and `learning. curve`  to select a `machine learning model`. At last evaluating the model using metrics like `recall`, `precision` and `f1-score`.

## Technologies Used
  
> [![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) is used as Programming Language.

>  `Numpy` and `Pandas` are used to work with the data.

> `Matplotlib` and `seaborn` is used to visualise the results.

> `Sciki-learn` is used for data preprocessing, creating machine learning model and evaluating it, thus creating a pipeline.

> `Pipenv` is the virtual environment used for the project. `Jupyter Notebook` is used to for the entire data science and machine learning life cycle.

## Results of the Project

#### Imbalanced Data

![Imbalanced Data](https://github.com/AkashSDas/Customer-Churn/blob/master/project-results-images/count.png)

#### Correlation Matrix

![Correlation Matrix](https://github.com/AkashSDas/Customer-Churn/blob/master/project-results-images/corr.png)
<hr>

#### `Cross Validation Score of Imbalanced Dataset`

![Cross Validation Score of Imbalanced Data](https://github.com/AkashSDas/Customer-Churn/blob/master/project-results-images/cross-val-score-before-smote.png)

<hr>

#### `Cross Validation Score of Balanced Dataset`

![Cross Validation Score of Balanced Data](https://github.com/AkashSDas/Customer-Churn/blob/master/project-results-images/cross-val-score-after-smote.png)

<hr>

#### Learning Curve

![Learning Curve](https://github.com/AkashSDas/Customer-Churn/blob/master/project-results-images/learning-curve.png)

#### Confusion Matrix

```python
                 precision    recall  f1-score   support

	0.0        0.80      0.80      0.80        45
	1.0        0.40      0.40      0.40        15

    accuracy                           0.70        60
   macro avg       0.60      0.60      0.60        60
weighted avg       0.70      0.70      0.70        60
```
## Installation

  

It is highly **recommended** to use **`virtual environment`** for this project to avoid any issues related to dependencies.

  

Here **`pipenv`** is used for this project.

  

There is a **`requirements.txt`** file in `'Customer-Churn'/requirements.txt` which has all the dependencies for this project.

  

- First, start by closing the repository

  

```bash
git clone https://github.com/AkashSDas/Customer-Churn
```

  

- Start by installing **`pipenv`** if you don't have it

```bash
pip install pipenv
```

  

- Once installed, access the venv folder inside the project folder

```bash
cd  'Customer-Churn'/venv/
```

  

- Create the virtual environment

```bash
pipenv install
```

The **Pipfile** of the project must be for creating replicating project's virtual environment.

  

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

  

- Enable the virtual environment

```bash
pipenv shell
```
- dataset, jupyter notebook and model are in `'Customer-Churn'/venv/src` folder.
```bash
cd src/
```

  

- To start/view the jupyter notebook

```bash
jupyter noterbook
```

  

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.
  

## License

  

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
