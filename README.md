Build different classification models from historical data of patients and their responses to different medications. Then you use the trained algorithms to predict the class of an unknown patient or to find a proper drug for a new patient.

About the dataset

Imagine that you are a medical researcher compiling data for a study. You have collected data about a set of patients, all of whom suffered from the same illness. During their course of treatment, each patient responded to one of 5 medications, Drug A, Drug B, Drug c, Drug x and y.Part of your job is to build a model to find out which drug might be appropriate for a future patient with the same illness. The feature sets of this dataset are Age, Sex, Blood Pressure, and Cholesterol of patients, and the target is the drug that each patient responded to.
You can use the training part of the dataset to build a logistic regression, decision tree, Random Forest, KNN, SVM, and Naive Bayes Classifiers and then use it to predict the class of an unknown patient, or to prescribe it to a new patient.


Downloading the Data
To download the data, we will use !wget to download it from IBM Object Storage.

!wget -O drug200.csv https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0101ENv3/labs/drug200.csv
