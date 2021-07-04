# Predicting Bike-Sharing Patterns
This is the first project of the Udacity Deep Learning Nanodegree Program.  

## Setting up the virtual environment

1. >pip install virtualenv
2. >python -m venv env
3. > cd .\env\Scripts
4. >activate
5. >pip install -r requirements.txt
6. >python -m ipykernel install --name=\<choose-a-name-to-be-displayed-in-jupyter\>

## Problem statement
As a bike sharing company, you want to predict the number of bikes you need. If you have too few you're losing money from potential customers and if you have too many you are wasting money (storage, maintenance etc.) for unused bikes.

## Solution
A simple neural network with one hidden layer consisting of 10 nodes is manually built with NumPy. Historical weather and rental data on an hourly basis is used for training and evaluating the network.
  
The following image exemplarily shows the prediction on a test set of 21 days:
![Prediction Image](/results.png)
