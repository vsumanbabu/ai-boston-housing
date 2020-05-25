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
1. CRIM - per capita crime rate by town
2. ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS - proportion of non-retail business acres per town.
4. CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
5. NOX - nitric oxides concentration (parts per 10 million)
6. RM - average number of rooms per dwelling
7. AGE - proportion of owner-occupied units built prior to 1940
8. DIS - weighted distances to five Boston employment centres
9. RAD - index of accessibility to radial highways
10. TAX - full-value property-tax rate per $10,000
11. PTRATIO - pupil-teacher ratio by town
12. BLACK - where Bk is the proportion of blacks by town
13. LSTAT - lower status of the population
#### Output Variable:
1. MEDV - Median value of owner-occupied homes in $1000's
