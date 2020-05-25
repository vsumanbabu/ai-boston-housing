# ai-boston-housing
AI Boston Housing

### Setup
1. Install Miniconda - https://docs.conda.io/en/latest/miniconda.html
2. conda env remove -n ds_base_env
3. conda env create -f ds_base_env.yaml
4. conda info --envs
5. conda env list
6. conda activate ds_base_env
7. jupyter notebook
8. conda deactivate


## Data sets

### Boston.csv
#### Features:
CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
BLACK - where Bk is the proportion of blacks by town
LSTAT - lower status of the population
#### Output Variable:
MEDV - Median value of owner-occupied homes in $1000's
