## Project 1: Predicting Churn Rate for Customers in a European Bank

**Project description:** This is a group project as part of the Data Science for Business 1 course at Aalto University.

A client of ours - an anonymous European bank serving France, Germany, and Spain markets - currently has a roughly 20% of churn rate which is almost double that of the industry average of 11%, according to a report by Accenture. Acting as their consultants, we are tasked with a simple mission: how to predict the characteristics of customers who are likely to churn in order to take targeted measures to those specific groups.

Our plan is to build three predictive models (Decision Tree, Support Vector Machine, and Logistic Regression) to predict if a customer with specific characteristics is more likely to churn. These models will be compared based on ROC, AUC, Accuracy score and Confusion Matrix in order to identify the most accurate model.

### 1. Importing Library

Importing the necessary libraries

```python
import pandas as pd
import numpy as np
import itertools
import matplotlib.pyplot as plt
from matplotlib import gridspec
import matplotlib.ticker as mtick
import scikitplot as skplt

import seaborn as sns

from sklearn.svm import SVC
from sklearn.linear_model import LogisticRegression

from sklearn.model_selection import train_test_split
from imblearn.over_sampling import SMOTE
from sklearn.decomposition import PCA

from sklearn.metrics import accuracy_score
from sklearn.metrics import confusion_matrix
from sklearn.metrics import roc_curve, auc

from collections import Counter
```

### 2. Importing data from CSV and Exploratory Analysis

```python
data = pd.read_csv('BankChurn.csv')
data.info()
```

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 10000 entries, 0 to 9999
Data columns (total 12 columns):
 #   Column            Non-Null Count  Dtype  
---  ------            --------------  -----  
 0   customer_id       10000 non-null  int64  
 1   credit_score      10000 non-null  int64  
 2   country           10000 non-null  object 
 3   gender            10000 non-null  object 
 4   age               10000 non-null  int64  
 5   tenure            10000 non-null  int64  
 6   balance           10000 non-null  float64
 7   products_number   10000 non-null  int64  
 8   credit_card       10000 non-null  int64  
 9   active_member     10000 non-null  int64  
 10  estimated_salary  10000 non-null  float64
 11  churn             10000 non-null  int64  
dtypes: float64(2), int64(8), object(2)
memory usage: 937.6+ KB

We can see that there are 10000 records and data provided was relatively clean (no missing values).

```python
data.describe().round()
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
