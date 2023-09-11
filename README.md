# Titanic Disaster Project : Project Overview

* Created a machine learning project that tends to predict whether passengers of Titanic ship survived the disaster or not.
* Collected the data to work with from kaggle website (from a competition called 'Titanic - Machine Learning from Disaster') already divided in train and test sets.
* Cleaned data up and engineered features so they will help us in the prediction process like extracting title of every passenger from their names.
* Optimized Logistic Regression, KNN, SVM, Gaussian NB, Perceptron, Linear SVC, Stochastic Gradient descent, Decision Tree and Random Forest classifiers to get the best training performance and the best estimator.

## Code and Resources used

<b>Python Version :</b>3.9<br>
<b>Packages :</b>Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, random<br>
<b>For Web Framework Requirements:</b> <code>pip install -r requirements.txt</code>

## Data Collection

Collect data from kaggle website so that training dataset has 891 passengers and test dataset has 418 passengers. With each passenger, we got the folowing :
* Passenger ID
* Column on whether each passenger survived the catastrophy or not (only available for training data)
* Passenger Class
* Name
* Sex
* Age
* Number of siblings and spouses
* Number of parents and children
* Type of ticket
* How much a passenger paid for the trip (Fare)
* Cabin used to sleep on the ship
* Port of Embarkation
