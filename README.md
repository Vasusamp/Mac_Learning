project title : Machine Learning - Predicting Phishing

Objective : The objective of this project is to predict the phishing websites efficiently using supervised machine learning algorithms.

Need of the Study : Phishing is one of the luring techniques used by phishing artist in the intention of exploiting the personal details of unsuspected users. Phishing website is a mock website that looks similar in appearance but different in destination. The unsuspected users post their data thinking that these websites come from trusted financial institutions. Several antiphishing techniques emerge continuously but phishers come with new technique by breaking all the antiphishing mechanisms. Hence there is a need for efficient mechanism for the prediction of phishing website. This project employs Machine-learning technique for modelling the prediction task and supervised learning algorithms namely Random Forest, Logistic Regression, SVM, Decision tree, Naïve bayes, KNN and SGD are used for exploring the results. It has been observed that the random forest classifier predicts the phishing website more accurately when comparing to other machine learning algorithms.

Data Sources : Everlytics

Tools : Python 

Techniques: Exploratory data analysis, data cleaning, Random Forest, Logistic Regression, SVM, Decision tree, Naïve bayes, KNN and SGD

Data Selection : The dataset contains 31 columns wherein 30 are features on the basis of which they are classified as Phishing website and 1 as target and the column name of the target variable is mentioned as "Result". it has 2456 observations.

The dataset was named as "Phish_Data". After importing the necessary packages, the excel dataset was successfully imported into Jupyter Notebook. Performed the fundamental exploratory data analysis operations such as head(), tail() and describe(). The info() function revelaed that the dataset contains integers. The dataset contains only three classes such as -1, 0, 1. The descibe() function revealed that 75% of observations belong to class 0. 

Histograms : The plot distribution of classes using histogram showed that 0 and 1 are predominant and -1 is in negligible amount. On comparison of classes 0 and 1, 0 is the major. 
Missing Values : There are no missing values in the dataset.

Correlation Matrix : The heatmap showed there is no significant correlation between the variables. 

Correlation with Target Variables : Generated the correlation of all features with target variables and features having correlation coefficents between  +/- 0.03 were removed in order to get higher accuracy. Around seven variables were removed. 

Prepare data for models : out of 31 variables, seven were removed and with 24 variables now the data is ready for model building.

Data Mining: To perform data mining over the dataset, the dataset is split into training and testing dataset. The split ratio is 70-30 wherein 70% accounts to training set nd the remaining 30% was used as test data.


Model Building :
In order to understand how different classifiers perform in terms of the accuracy, following classifiers were attempted. 

1. Random Forest

At First, attempted to build model using Random Forest Classifier. The confusion matrix obtained was given as shown below.

Random Forest	Actual / Yes	Actual / No
Predicted  / Yes	      403	         11
Predicted / No	        13	         310

The accuracy using Random Forest classifier is 97%
2. Linear regression
Then Linear regression was attempted. The confusion matrix is as shown below.

Linear Regression	Actual / Yes	Actual / No
Predicted  / Yes	          383	         22
Predicted / No	            23	         309

The accuracy using Linear regression classifier is 94%

3. SVM
The support vector machine's confusion materix is given as shown below.

SVM	Actual / Yes	Actual / No
Predicted  / Yes	  393	   21
Predicted / No	    16	   307

The accuracy using SVM is 93%

Conclusion
The aim of this project is to predict whether the given URL is a phising website or not. This project involved the dataset from Evelytics and applied Python programming to evaluate various machine learing algorithms. The goal is to find the best classifier as far as the accuracy is concerned. Random forest classifier turns out to be the best classifier based on the accuracy of 97%. Logistic regression produced 94% accuracy and SVM produced 93%.

