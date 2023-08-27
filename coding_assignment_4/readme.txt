Implement a Naive Bayes classifier for the Iris dataset, which is organized into a data frame downloaded from sklearn using the following Python snippet:
 
import pandas as pd
from sklearn.datasets import load_iris
data = load_iris()
temp = {}
temp['data'] = data['data'].tolist()
temp['target'] = data['target'].tolist()
df = pd.DataFrame(temp)
 
Use your classifier to determine which target the following data points belong to:
[5.0, 3.1, 2.4, 1.6], [5.0, 3.1, 2.1, 0.6], [6.0, 3.1, 5.5, 2.0]
Note: You need to code a Naive Bayes classifier yourself. You'll receive a zero automatically if you simply import and use a Naive Bayes classifier from an existing package.
