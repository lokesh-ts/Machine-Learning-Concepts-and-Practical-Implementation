# Summary:
# Project Abalone 
8 features:  
Applying PCA.PCA-80% of variance  

----------------
Importing packages:  
import numpy as np  
import matplotlib.pyplot as plt  
%matplotlib inline  
import seaborn as sns  
import pandas as pd  
sns.set()  

Data Loaded using:  
url = "https://archive.ics.uci.edu/ml/machine-learning-databases/abalone/abalone.data"  
df = pd.read_csv(url, header=None)

-----------------
we come to know that,How many principal components we can combine or utilize to attain or explain the underlying variability of the data.  
This the purpose of this project.This is how we actually use PCA.
