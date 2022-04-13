# Coding assignment

### Introduction

This repository contains the coding assignment "Create lead generator". One CSV-datafile was handed to generate a model that predicts whether or not a given contact will be a potential customer of the product.
To tackle this challenge, a self-trained model was implemented in order to handle the huge amount of unlabelled data. In this context, unlabelled means no contact with that observation took place in the past (*b_in_kontakt_gewesen*).

### Notebooks

The work consists of two notebooks, please read and work through them in the following order:

1. [Exploratory Data Analysis (EDA)](/EDA.ipynb)
2. [Preprocessing and Model implementation](/Preprocessing_and_Model.ipynb)

In the first notebook, a full exploratory data analysis (EDA) is done. The preprocessing, model building and application can be found in the second notebook.

### Environment

The Python version 3.9.4 was used, which can be installed using pyenv in a virtual environment:

```
pyenv local 3.9.4
python -m venv .venv
source .venv/bin/activate
```

In order to install the required libraries, the following command line is recommended:

```
pip install -r requirements.txt

```
