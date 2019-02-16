# Predicting-Boston-Housing-Prices
Model Evaluation & Validation Project [Udacity Machine Learning Engineer Nanodegree]

## Project Overview
### Project Description
Develop a model to predict Boston housing prices. Utilize sklearn techniques for training, testing, evaluating and optimizing models.

### Project Procedure
- Explore the data
- Develop a model using decision tree algorithm
- Optimize model parameters using grid search
- Predicting selling prices for 3 clients

### Project Results
- Predicted sellling price

  |  | home price | 
  | :---:   | :-: | 
  | client 1 | $409,100.00 |
  | client 2 | $285,600.00 |
  | client 3 | $957,218.18 |

- Applicability of the constructed model

  Still have a big room to improve before being used in the real-world for below reasons:
  - The mdoel learn from a old dataset which has quite different value of money from current, so it will not able to make a accurate prediction for house price nowadays.
  - More features relevant to house prices should be considered such as location, economic growth and interest rate, etc.


## Getting Started
### Prerequisites

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

### Run

In a terminal or command window, run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
