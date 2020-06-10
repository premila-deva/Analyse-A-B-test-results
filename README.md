# Analyse-A-B-test-results  
A/B tests are very commonly performed by data analysts and data scientists.   
This is a Udacity project in Data Analyst Nano degree. For this project, I will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Goal is to work through notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.  

**Libraries to import**  
import pandas as pd    
import numpy as np  
import random  
import matplotlib.pyplot as plt   

from sklearn.model_selection import train_test_split  
from sklearn.linear_model import LogisticRegression  
from sklearn.metrics import precision_score, recall_score, accuracy_score, confusion_matrix  
