# Statistical-Analysis-of-Titanic-Dataset-along-with-Machine-Learning-Model

There are three primary work in this notebook:

Do a statistical analysis of how some group of people was survived more than others.

Do an exploratory data analysis(EDA) of titanic with visualizations and storytelling.

Predict: Use machine learning classification models to predict the chances of passengers survival.

Dataset Description

Features

Categorical Variables:

Nominal:

Cabin

Embarked (Port of Embarkation: C - Cherbourg, Q - Queenstown, S - Southampton)

Dichotomous:

Sex (Female, Male)

Ordinal:

Pclass (Proxy for socio-economic status: 1 - Upper, 2 - Middle, 3 - Lower)

Numeric Variables:

Discrete:

Passenger ID (Unique identifier)

SibSp (Number of siblings/spouses aboard)

Parch (Number of parents/children aboard)

Survived (Outcome/dependent variable: 0 - Did not survive, 1 - Survived)

Continuous:

Age

Fare

Text Variables:

Ticket (Passenger's ticket number)

Name (Passenger's name)

Data Split

Training Set (train.csv):

Includes the target variable - Survived

Used to train and validate machine learning models

Test Set (test.csv):

Does not contain the Survived variable (to predict using the developed model)

Used to assess the model's performance on unseen data

