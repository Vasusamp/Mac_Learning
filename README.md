project title : Machine Learning - Predicting Phishing

Objective : The objective of this project is to predict the phishing websites efficiently using supervised machine learning algorithms.

Need of the Study : Phishing is one of the luring techniques used by phishing artist in the intention of exploiting the personal details of unsuspected users. Phishing website is a mock website that looks similar in appearance but different in destination. The unsuspected users post their data thinking that these websites come from trusted financial institutions. Several antiphishing techniques emerge continuously but phishers come with new technique by breaking all the antiphishing mechanisms. Hence there is a need for efficient mechanism for the prediction of phishing website. This project employs Machine-learning technique for modelling the prediction task and supervised learning algorithms namely Random Forest, Logistic Regression, SVM, Decision tree, Naïve bayes, KNN and SGD are used for exploring the results. It has been observed that the random forest classifier predicts the phishing website more accurately when comparing to other machine learning algorithms.

Data Sources : Everlytics

Tools : Python 

Techniques: Random Forest, Logistic Regression, SVM, Decision tree, Naïve bayes, KNN and SGD

Data Importing : The dataset contains 2456 rows and 31 columns. The column name of the target variable is mentioned as "Result".

The dataset was named as "Phish_Data". After importing the necessary packages, the excel dataset was successfully imported into Jupyter Notebook. Performed the fundamental exploratory data analysis operations such as head(), tail() and describe(). The info() function revelaed that the dataset contains integers. The dataset contains only three classes such as -1, 0, 1. The descibe() function revealed that 75% of observations belong to class 0. 
