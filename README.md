# KNN-for-mixed-data
The KNeighborsClassifier of sklearn package rests mainly on Euclidian distance and some other metrics that are suitable only to quantify the similarity between two observations for numerical variables, and for the categorical ones. So our purpose is to find out how to exploit these metrics on a mixed data so that we can apply the KNN algorithm.
We apply the Multiple correspondence analysis on only categorical data, on subset from them 85% of information, and transdorm it on numerical data, that is the coordinate of each ibservation on 30 components. 
Tis approach has realized an accuracy of 91% on test data.
