# Titanic_Survival_Prediction


## Titanic Survival Prediction using Machine Learning


## 1. Problem Statement
The Titanic dataset provides observations for each passengenger and the survival outcome.The problem statement entails predicting whether a passenger would survive or not survive given the features such as passenger class, sex, fair, age, number of siblings/spouse abroad, number of parents/children abroad, and other. 

## 2. Data Description

Data is obtained from Titanic survival Prediction Kaggle Competition.
https://www.kaggle.com/c/titanic/data

* Number of instances - 891
* Number of Attributes - 12
  * Attribute breakdown - 11 quantitative inputs, 1 quantitative output

#### Attribute information
##### Inputs
* Name
* Sex
* Age
* Pclass (Passenger Class)
* SibSp (Siblings/Spouse)
* Parch ( Parents/Children)
* Cabin
* Embarked
* Fare
* Ticket
* PassengerId


##### Output
* Survived (Yes/No)

## 3. Modelling and Evaluation

* Algorithms used
  * Logistic regression
  * KNeighboursClassifier
  * Decision Trees
  * Random Forests
  * GaussianNB 
  * SVC

* Evaluation Metric - Accuracy_score and Confusion Matrix.

## 4. Exploratory Data Analysis

#### Visualization of Plots
![Feature correlation](https://github.com/rakshit2508/Team-10-Project/blob/main/imgs/corr.png)
#### Feature importance
![Feature importance](https://github.com/rakshit2508/Team-10-Project/blob/main/imgs/FEATUREIMPORTANCE_CSP.png)
#### Final Comparison
![Final Comparison](https://github.com/rakshit2508/Team-10-Project/blob/main/imgs/RMSE_FINAL_CSP.png)


## 5. References
1. https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength
