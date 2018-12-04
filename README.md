# Programming languages:
python3 in Jupyter

# required packages:
sklearn.datasets.make_classification. 
sklearn.linear_model.SGDClassifier  
pandas   
numpy   
time
keras.models.Sequential  
keras.layers.Dense  
keras.layers.Dropout  

# import:
from sklearn.datasets import make_classification  
from sklearn.linear_model import SGDClassifier  
import pandas as pd  
import numpy as np  
import time  
from keras.models import Sequential  
from keras.layers import Dense  
from keras.layers import Dropout   

# model
Using nn which has 2 layers. Each layer has 750 neural units. 

# This is MSBD5001 individual project in HKUST

# Description
This competition is about modeling the performance of computer programs. The dataset provided describes a few examples of running SGDClassifier in Python. The features of the dataset describes the SGDClassifier as well as the features used to generate the synthetic training data. The data to be analyzed is the training time of the SGDClassifier.

# Evaluation Metric
The evaluation metric used is mean-squared error. Lower error leads to a higher ranking.
The competition link is ： https://www.kaggle.com/c/msbd5001-fall2018
