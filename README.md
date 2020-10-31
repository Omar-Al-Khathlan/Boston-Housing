# Machine Learning Course
# Supervised Learning
## Project: Boston Housing

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

I recommend installion [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Code

Template code is provided in the `Number_of_Rooms_Predicition.ipynb` notebook file.

### Run

In a terminal or command window, navigate to the top-level project directory `Boston-Housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Number_of_Rooms_Predicition.ipynb
```  
or
```bash
jupyter notebook Number_of_Rooms_Predicition.ipynb
```

This will open the iPython Notebook software and tutorial file in your browser.

### Data
The dataset originally came from here: https://github.com/selva86/datasets/blob/master/BostonHousing.csv

**Origin: **The origin of the boston housing data is Natural.
    
**Number of Cases: **The dataset contains a total of 506 cases.

**Features**
 - CRIM    : per capita crime rate by town.
 - ZN      : proportion of residential land zoned for lots over 25,000 sq.ft.
 - INDUS   : proportion of non-retail business acres per town.
 - CHAS    : Charles River dummy variable (1 if tract bounds river; 0 otherwise).
 - NOX     : nitric oxides concentration (parts per 10 million).
 - AGE     : proportion of owner-occupied units built prior to 1940.
 - DIS     : weighted distances to five Boston employment centres.
 - RAD     : index of accessibility to radial highways.
 - TAX     : full-value property-tax rate per $10000.
 - PTRATIO : pupil-teacher ratio by town.
 - B       : 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
 - LSTAT   : % lower status of the population.
 - MEDV    : Median value of owner-occupied homes in $1000's.

**Target Variable**
 - RM      : average number of rooms per dwelling.
