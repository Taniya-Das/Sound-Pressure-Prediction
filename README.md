# Sound-Pressure-Prediction-using-Linear-Regression

---

## Problem Statement

Predict sound pressure level for airfoil blade sections when  from a series of aerodynamic and acoustic tests is conducted in an anechoic wind tunnel. 

## Method Used

I have performed a regression analysis using Linear Regression model to predict the sound pressure level. Analysis is done in two ways first in where linear regression is performed using sklearn's build-in library and second is by writing my own functions for computing cost and gradient descents. Lastly, root mean square error (RMSE) metric is used to access the model's performance, wherein both the ways have yielded similar RMSE.  


## Dataset

The dataset is downloaded from [UCI Machine Learning repository](https://archive.ics.uci.edu/ml/datasets/Airfoil+Self-Noise). 
The data consists of 1503 entries, each having 5 features.
<br \> Target variable: Sound_pressure_level 

First five entries of the dataset:
<img width="623" alt="Capture" src="https://user-images.githubusercontent.com/30569154/123829819-62850e00-d920-11eb-8504-b93f25997637.PNG">


## Reference

Thanks to Hackerearth for putting out this tutorial [linear regression analysis using R](https://www.hackerearth.com/practice/machine-learning/machine-learning-algorithms/beginners-guide-regression-analysis-plot-interpretations/tutorial/).
