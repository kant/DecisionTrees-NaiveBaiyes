# DecisionTrees and NaiveBayes implementation in python
 Implementation of Naive Bayes and Decision Trees in python 2
 Multiclass classification problem.
 
 Problem :
The dataset is a collection of 1500 tweets. The tweets
have the word “congress” in them which may refer to the Mobile World Congress,
Indian National Congress and so on. The aim of the code is to disambiguate
the same into three classes – Mobile World Congress(3), Indian National Congress(2)
and Others(1).
 
 Dataset: 
   The dataset consists tweets of three classes. 
   Class 1 - Tweets regarding other type of congress
   Class 2 - Tweets regarding Indian National Congress
   Class 3 - Tweets regarding mobile world Congress
   
stopwords.txt contains stopwords in a text file. This will in preprocessing data
1200 tweets are used for training, while the rest 300 are used for testing the algorithm
The file naive.py contains code for Naive Bayes algorithm. 
The file decision.py conatins code for Decision Trees. ID3 algorithm is used. 

Accuracy:
Decision Trees: 98.33%
Naive Bayes: 99%
