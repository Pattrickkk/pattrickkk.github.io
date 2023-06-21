## Portfolio

---

### Project 1: Predicting Churn Rate of Customers in a European Bank

This project is a part of the course Data Science for Business 1 at Aalto University. The dataset was downloaded from Kaggle, which contains data that has already been cleaned. The goal of the project was to build different predictive models so as to predict whether a customer is likely to churn or not from the bank. Due to the imbalance of the data (20% churn / 80% stay), I also implemented SMOTE to rebalance the data. However, the model is built from both original and balanced data.
<br>
<br>
3 methods were use to build 6 different models: Decision Tree (with default parameters), Logistic Regression, and Support Vector Machine. Based on the Confusion Matrix and the ROC curve, it was concluded that Decision Tree models performed the best on the test set (30%). Furthermore, hyperparameter tuning was done for *max_depth*. However, the improvement of accuracy was minimal.
<br>
<br>


<img src="images/1.png?raw=true"/> <br>
[Python Notebook](https://nbviewer.org/urls/pattrickkk.github.io/python/Project1.ipynb) <br>
[Presentation](/pdf/Project1_Presentation.pdf) <br>

---
### Project 2: Natural Language Processing - Analyzing Amazon Reviews of Xbox and PlayStation

This project is a module of the course Data Science for Business 2 at Aalto University. The dataset provided contains text-based Amazon review of 2 products: Xbox and PlayStation. Bag of Words approach was used for this project. I created new function to clean the text (remove symbols, URL, punctuation, special characters, etc.) as well as convert list to string and remove stopwords. Reviews were also categorized as negative (rating=1,2,3) and positive (rating=4,5).
<br>
<br>
For each product, I created a separate wordcloud for positive and negative reviews to identify what people compliment or complain about.
<br>
<br>
Last but not least, I built classifier model based on Naive Bayes Classifier method to predict the sentiment of the review based on text. The result was evaluated based on Accuracy score, precision, Recall, F1 score as well as Confusion Matrix.
<br>
<br>

<img src="images/2.png?raw=true"/><br>
[Python Notebook](https://nbviewer.org/urls/pattrickkk.github.io/python/Project2.ipynb) <br>
[Report](/pdf/Project2-Report.pdf) <br>

---
### Project 3: Survival Analysis - Predicting Survival Rate of E-Scooters

<img src="images/3.png?raw=true"/> <br>
[Python Notebook](https://nbviewer.org/urls/pattrickkk.github.io/python/Project3.ipynb) <br>
[Report](/pdf/Project3_Report.pdf) <br>

---
### Project 4: Optimizing Supply Chain Network of REIMA

<img src="images/4.png?raw=true"/> <br>
[Python Notebook](https://nbviewer.org/urls/pattrickkk.github.io/python/Project4.ipynb) <br>
[Report](/pdf/Project4_Report.pdf) <br>
[Presentation](/pdf/Project4_Presentation.pdf) <br>

---
### Project 5: Tableau Challenge 2023

<img src="images/5.png?raw=true"/><br>
[Report](/pdf/Project5_Presentation.pdf) <br>

---
### Project 6: Tourism Report for Uusimaa on PowerBI

<img src="images/6.png?raw=true"/><br>
[Report](/pdf/Project6_Presentation.pdf) <br>

---
### Project 7: Predicting Support Rate of Different Political Parties in Finland

<img src="images/7.png?raw=true"/><br>
[Python Notebook](https://nbviewer.org/urls/pattrickkk.github.io/python/Project7.ipynb) <br>
[Report](/pdf/Project7_Presentation.pdf) <br>
