# Implementation of system that can predict the PM2.5 level using data of Five Chinese Cities Data Set

This repository will go through implementation of PM2.5 level prediction in China

What is PM2.5 and Why You Should Care
PM2.5 readings are often included in air quality reports from environmental authorities and companies. 
Find out what they mean and why you should monitor their levels.

PM2.5 refers to atmospheric particulate matter (PM) that have a diameter of less than 2.5 micrometers, 
which is about 3% the diameter of a human hair.

Commonly written as PM2.5, particles in this category are so small that they can only be detected with an electron microscope. 
They are even smaller than their counterparts PM10, which are particles that are 10 micrometres or less, 
and are also called fine particles.


Using publicly available dataset (https://archive.ics.uci.edu/ml/datasets/PM2.5+Data+of+Five+Chinese+Cities) 
we have cleaned and prepared data first. You may find code for each step in Data Preparation folder. 

You can find full dataset here (https://drive.google.com/drive/folders/1xLOHx1lcCQzHe1rJxsyxYFRx4NPJwAfd?usp=sharing)

Once we prepared full dataset, using various Machine Learning algorithms we tried to solve Regression problem. 

* Linear Regression
* Decision Tree
* Random Forest

We have achieved about 90% of R2 score on TEST SET. 

However, you can get more if you play with dataset and increase number of features, making feature engineering; or fine-tune models more.

Have fun!
