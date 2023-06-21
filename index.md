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

This project is a module of the course Data Science for Business 2 at Aalto University. The dataset includes 283 observations of 283 scooters with 7 attributes. Using Kaplan Meier Estimator, a survival analysis is conducted with the historical data to build a survival analysis model to predict the survival rate of the scooters. Moreover, we look into the difference between scooters made by manufacturers A, B, and C.
<br>
<br>
I used log-rank test p-value to confirm that there are difference in the survival rate between scotters made by manufacturors A, B, and C. After this, I built 2 models: Cox Regression and Random Survival Forest (RSF) to predict the survival rate of the scooters. The RSF model is then used to predict the survival rate of 10 new scooters which were not included in the dataset.
<br>
<br>

<img src="images/3.png?raw=true"/> <br>
[Python Notebook](https://nbviewer.org/urls/pattrickkk.github.io/python/Project3.ipynb) <br>
[Report](/pdf/Project3_Report.pdf) <br>

---
### Project 4: Optimizing Supply Chain Network of REIMA

This project is part of a Supply Chain Capstone course, in collaboration with Reima, Fazer and Meluton. This was a group project, however, there were 2 people in my group (me included) and the other student did not have any analytics skills so I took care of all the analytics work, including:
<br>- Conduct time series analysis to predict future sales (based on ARIMA method) from historical sales per market per product category (Python)
<br>- Locate the optimized location of Reima warehouse using center-of-gravity method (Excel Solver)
<br>
<br>
I received a score of 90/100 for this course and Reima representatives commented that my sales forecast was very accurate compared to their forecast. 
<br>
<br>
<img src="images/4.png?raw=true"/> <br>
[Python Notebook](https://nbviewer.org/urls/pattrickkk.github.io/python/Project4.ipynb) <br>
[Report](/pdf/Project4_Report.pdf) <br>
[Presentation](/pdf/Project4_Presentation.pdf) <br>

---
### Project 5: Tableau Challenge 2023

This is a group project as part of a Business Intelligence Capstone course at Aalto University. The dataset provided contains traffic accidents information across Finland. After doing individual exploratory analysis of the data, I found out that the best approach for dividing the work within the team would be for each member to look into the insights of one type of accident (Car, Bicycle, Pedistrian, Animal-Related, etc.)
<br>
<br>
My team was selected as one of the top 5 best groups from Aalto University, in order to participate in the Official Tableau Challenge, with the participation of 5 teams from Turku University. Unfortunately, I was not able to join the event due to prior commitment at work.
<br>
<br>
<img src="images/5.png?raw=true"/><br>
[Report](/pdf/Project5_Presentation.pdf) <br>

---
### Project 6: Tourism Report for Uusimaa on PowerBI

This is an individual project as part of a Business Intelligence Capstone course at Aalto University. The dataset provided include reviews from different hotels in Finland. I was tasked to write a report on any insights of the tourism industry in the Uusima region. All pages of the report was made on PowerBI.
<br>
<br>
<img src="images/6.png?raw=true"/><br>
[Report](/pdf/Project6_Presentation.pdf) <br>

---
### Project 7: Predicting Support Rate of Different Political Parties in Finland

This project was not a part of any university course, but instead an "exercise" that I completed when I was applying to an internship at Nordic Investment Bank. Even though I did not get selected in the end, I had a lot of fun working on this. The dataset provided include support rate (in %) of each municipality in Finland for different political parties. Based on the dataset, I built predictive models to help predict how much the each municipality will support each party, based on different attributes (foreigner rates, employment rate, etc.).
<br>
<br>
The model building was done on Python/Google Colab and the graphs were made by PowerBI.
<br>
<br>
<img src="images/7.png?raw=true"/><br>
[Python Notebook](https://nbviewer.org/urls/pattrickkk.github.io/python/Project7.ipynb) <br>
[Report](/pdf/Project7_Presentation.pdf) <br>
