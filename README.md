# Team TRIAJ

Trevor Caldwell

Robin Stewart

Ilya Getsin

Aqeel Ali

Jamal Hamadeh
___
## Table of Contents


1. [Overview](#Overview)
    1. [The Data](#The-Data)
    1. [Project Goals](##Project-Goals)
1. [Data Wrangling](##Data-Wrangling)
1. [EDA](#EDA)
    1. [Importing & DataFraming](##Importing-&-DataFraming)
    
1. [Model Analyses](#Model-Analyses)
1. [Visualizations](#Visualizations)
    1. [Slide Deck](https://docs.google.com/presentation/d/1iIjkURRV3yMbMUNnj3k_r3jpHNOrMHAOR2SaIU2j2O8/edit?usp=sharing)
---

# Overview 

## The Data

[Desc of data set here]

### Forecasting HIV Incidences

## Project Goals


1. ***Forecasting HIV incidence*** in US using Linear regression.
2. Forecast the number of HIV Incidences ***by county ***

# Data Wrangling

1. Initially exploring a pandas scatter matrix of all the columns, assessing for any visible linear relationsip
2. Dropping columns of irrelevance or presenting multicollinearity (i.e. MSM5yrs and MSM12months - the same info for MSM12months is captured in MSM5yrs)

[Insert scatter matrix plot here]

# EDA


## Discovery

Notable features were:




# Model Analyses



# Visualizations



1. [Slide Deck](https://docs.google.com/presentation/d/1iIjkURRV3yMbMUNnj3k_r3jpHNOrMHAOR2SaIU2j2O8/edit?usp=sharing)


# Deliverables Summary


### What you planned to accomplish?

Building a model for predicting HIV Incidences, optimizing that model, and then repeat the process for predicting vulnerability (Likelihood estimate) of HIV Incidences *by county*. 

### How you organized yourselves as a team (including your git workflow)

### Description of the problem and the data

### What you planned to accomplish?

### Performance on unseen data


### What you accomplished (how you chose model, performance metric, validation)

- First round of model optimization
- Hyperparameter testing (# folds)
- 



Anything new you learned along the way

`DataFrame.corr()['target_col_name']` is ***VERY*** useful