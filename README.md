# A study on SMS Spam Classification using Naive Bayes.
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. 
It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
The objective is to build a model to classify and predict if a SMS tagged messages is a ham or spam.

`Predictors:`
```
text
```

`Target:`
```
Spam (0: Not Spam, 1: Spam)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://github.com/zhenyu92/ML_Naive_Bayes_Spam_Classification/blob/master/emails.csv).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_Naive_Bayes_Spam_Classification/blob/master/Naive%20Bayes%20-%20Spam%20Classifier.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Visualizing the Variables
      3.2 Data Cleaning
    4 Train Test Split
    5 Select and Train a Model
      5.1 5.1 Naive Bayes Model
    6 Apply Model on Test Set
    ```   

### Model Performance
The model has an average `Precision` and `Recall` of 99%.
![alt text](https://github.com/zhenyu92/ML_Naive_Bayes_Spam_Classification/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
