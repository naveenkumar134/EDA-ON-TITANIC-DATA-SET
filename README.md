
THIS IS EDA PROJECT ON TITANIC DATA SET
The titanic and titanic2 data frames describe the survival status of individual passengers on the Titanic. The titanic data frame does not contain information from the crew, but it does contain actual ages of half of the passengers.
Step 1: Importing basic libraries. import numpy as np import pandas as pd import seaborn as sns import matplotlib.pyplot as plt %matplotlib inline.
Step 2: Reading the data. ...
Step 3: Data Exploration. ...
Step 4: Feature Engineering. ...
Step 5: Data preprocessing for model. ...
Step 6: Model Deployment.
above insights can be derived from the exploratory data analysis without the use of any machine learning algorithm. There were still many other theories and hypotheses that tried to explain the survival data.
It gives you information about multiple people like their ages, sexes, sibling counts, embarkment points and whether or not they survived the disaster. Based on these features, you have to predict if an arbitrary passenger on Titanic would survive the sinking.
Compute mean of each Pclass/Sex group in the training set.
Map all NaN values in the training set to the right mean.
Map all NaN values in the test set to the right mean (lookup by Pclass/Sex and not based on indices)
