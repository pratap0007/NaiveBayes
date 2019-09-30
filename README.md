
# Naive Bayes Classifier 
Pridiction of ondet Diabetes using Naive Bayes Classifier.
# Dataset : Pima Indians Diabetes dataset
https://www.kaggle.com/uciml/pima-indians-diabetes-database#diabetes.csv


# Approach
step1. For reading dataset I have been used pandas


step2: labels for discretization ie. low,medium,high

step3 : For Preprocess the data means Traversing each feature of data  and replacing the missing values with the mean of that feature. Further, converting the numerical data to nominal data. We convert the numeric data to nominal data using the pandas.cut()



step4 : Create a function to traverse through the feature and count the number of occurrences of a nominal value and create a list to store our prediction.

step5 :Split the dataset into train and test data

step6: For training  the model by traversing through all the features and calculate the probabilities of all the unique categorical values,store these probabilities in the dictionary.



step7:for evaluate to model i have  create a confusion matrix.
By comparing the test set and the predicted list i have count the number of :

TP: Actual Yes Predicted Yes
TN: Actual No Predicted No

FP: Actual No Predicted Yes
FN: Actual Yes Predicted No




