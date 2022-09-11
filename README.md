# FNN-Network-to-solve-a-Multi--class-classification-problem
Build a FFN Network to solve a Multi- class classification problem
# Importing Libraries
```python
import pandas as pd
import numpy as np
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.model_selection import train_test_split
from sklearn.naive_bayes import MultinomialNB
```
# Loading Dataset
```python
data = pd.read_csv("bbc-news-data.csv", sep='\t')
print(data.head())
```
# Custom Classification
```python
user = input("Enter a Text: ")
data = cv.transform([user]).toarray()
output = model.predict(data)
print(output)
```
