# IrisFlowersClassification
This model classifies Iris flowers among three species (Sestosa, Versicolor and Virginica) from measurements of length and width of sepals and petals.

## Problem Statement:
The aim is to classify Iris flowers among three species (Sestosa, Versicolor and Virginica) from measurements of length and width of sepals and petals. 
After the completion of model, the computer should have the ability to aggregatethree different classifications of Iris flower to three categories.

## Dataset:
The dataset is a CSV file which contains a set of 150 records under 5 attributes -
Petal Length, Petal Width, Sepal Length, Sepal width and Class(Species)
Dependent Variables : Sepal length, Sepal Width, Petal length, Petal Width
Independent/Target Variable : Class
Missing values : None

## Steps for Problem Solving:
1. Loading the Iris Flower Classification Dataset from SKlearn inbuilt datasets
2. Dividing Features and Labels into different variables.
3. The dataset is divided into Train and Test data with 70:30 split ratio where
70% data is training data where as 30% data is test data. Random State is set
to 42 which avoids splitting of dataset differently on every run.
4. Importing Classifier from SKlearn and creating instance of classifier in a
“classifier” variable. 
5. Importing accuracy_score from SKlearn to check the accuracy of our model
against the test set.


## Result Analysis
The accuracy of model is 96.67% with Logistic Regression, 100% with K-nearest Neighbors algorithm, 100% with Decision Tree Classifier

## Reason for High Accuracy :
We can observe that there are relatively few features in the Iris dataset. Also, we
can see that Petal.width feature is very highly correlated with the class outcomes.
