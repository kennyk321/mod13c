# mod13c
### Package Requirments & Versions
`pip install x` x represents below packages
import pandas as pd
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder


### Purpose of Use
* Create model that predicts applicants success if funded by Alphabet Soup by creating binary classifier model. 

* The code is multiple parts:
    1. Prep data for use on neural network model
    2. Compile and evaluate binary classification model using neural network
    3. Optimize neural network model
    
    
### Files Navigation
* `GC_venture_funding_with_deep_learning.ipynb`: Code explanation and building
* `applicants_data.csv`