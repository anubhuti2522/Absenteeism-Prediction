# Absenteeism-Prediction
Used python to create a Machine Learning Algorithm based on the data that can predict the reason of absence of the employees. Built classification model and used Logistic Regression to predict the best accuracy of the model.<br>
There are two python file:
1. <b>Data_preprocessed.ipynb</b>: contains the code to preprocess the raw data. Classification method is done to group the reasons into sqparate columns according the reason for absence. Finally, the file is exported as <b>'Absenteeism_preprocessed.csv'</b><br>
2. <b>Absenteeism.ipynb</b>: contains the code to predict the preprocessed data using <b>Logistic Regression</b>. Classifying people into two clasees by using Absenteeism Time: <br>
1)Moderately Absent(<=3hours)<br>
2)Excessively Absent(>=4hours)<br><br>
Standardized the model and then predicted the accuracy for the training set and the testing set. Finally, save the file using pickel[module] to convert object into a character stream.
