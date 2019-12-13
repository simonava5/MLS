# Machine Learning & Statistics Module
### Project by Simona Vasiliauskaite
### Analysis of Boston Housing Database

In this assessment I will be using **Python** packages scipy, keras and jupyter notebook to describe and analyse the well-known Boston House Prices dataset. 

There are 14 attributes in each case of the dataset. They are:
* CRIM - per capita crime rate by town
* ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
* INDUS - proportion of non-retail business acres per town.
* CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
* NOX - nitric oxides concentration (parts per 10 million)
* RM - average number of rooms per dwelling
* AGE - proportion of owner-occupied units built prior to 1940
* DIS - weighted distances to five Boston employment centres
* RAD - index of accessibility to radial highways
* TAX - full-value property-tax rate per $10,000
* PTRATIO - pupil-teacher ratio by town
* B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
* LSTAT - % lower status of the population
* MEDV - Median value of owner-occupied homes in $1000's

*Note. Variable #14 seems to be censored at 50.00 (corresponding to a median price of $50,000); Censoring is suggested by the fact that the highest median price of exactly $50,000 is reported in 16 cases, while 15 cases have prices between $40,000 and $50,000, with prices rounded to the nearest hundred.

In this respitory you'll find a **Jupyter** Notebook called *BostonHousing.ipynb* which summarises the Boston House Prices dataset using descriptive analysis and plots.

Within the same Jupyter Notebook you will also find an analysis of the relationship between the median house price and whether the houses are more expensive alongside the river. Inferential statistics was used to analyse this section.

* *Inferential statistics* use a random sample of data taken from a population to describe and make inferences about the population.

The last part of the project is dedicated to using **Keras** to create a neutral network that can predict the median house price based on the other variables in the dataset.

In order to run this program, you need to install Python through Anaconda and install the following packages:

1. Scipy
2. Keras 
3. Jupyter Notebook

Please see below on how to install each package with conda run:

* Scipy - conda install -c anaconda scipy
* Keras - 
    1. conda install -c anaconda tensorflow (do this first)
    2. conda install -c anaconda keras (then this)

To run Jupyter Notebook:
```Jupyter Notebook```
