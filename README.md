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

#### Visualization Correlation Between Embarked, Sex and Survived 
![Visualization Correlation Between Embarked, Sex and Survived ](https://github.com/rakshit2508/Titanic_Survival_Prediction/blob/main/imgs/Embarked_Sex_Survived.png)
#### Visualization Correlation Between P_class, Age and Survived 
![Visualization Correlation Between P_class, Age and Survived ](https://github.com/rakshit2508/Titanic_Survival_Prediction/blob/main/imgs/P_class_Age_Survived.png)
#### Visualization Correlation Between P_class, Age, Sex and Survived 
![Visualization Correlation Between P_class, Age, Sex and Survived ](https://github.com/rakshit2508/Titanic_Survival_Prediction/blob/main/imgs/P_class_Age_Sex_Survived.png)


## 5. References
1. https://www.kaggle.com/c/titanic
