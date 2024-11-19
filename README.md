## classification-challenge
Module 13 Challenge

# Overview
In this Challenge, we compared models that predicted if an email was Spam. We compared the Logistic Regression model with a Random Forest Classifier to see which would predict more accurately. 

# Installation instructions
*For data and training preparation:*  <br>
import pandas as pd  <br>
from sklearn.model_selection import train_test_split  <br>
from sklearn.metrics import accuracy_score  <br>
*For scaling features:*  <br>
from sklearn.preprocessing import StandardScaler  <br>
*For comparing models:*  <br>
from sklearn.linear_model import LogisticRegression  <br>
from sklearn.ensemble import RandomForestClassifier

# Usage and conclusions
When looking at how the models perform, although the Random Forest Classifier had a higher accuracy score, the Logistic Regression model performed better. The model scores of the LR model are closer in value, so we know the data set has been well trained. There is a bigger difference in the model scores of the RFC, suggesting the training model may be overfit. 

