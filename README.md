# Classifying and predicting political affiliation with Naive Bayes
## #Bayes #Python 

The aim is to classify and predict the political affiliation of a person. A bayesian approach is suggested. 
The **prior and conditional probabilities** were computed and stored in the form of dictionaries. Aftewards,
the **posterior probability** was calculated as the product of the prior and the conditional probability. For example:


        P(democrat|D) = P(D|democrat)*P(democrat)
                        _________________________
                                  P(D)
In the case of numeric features, the **probability density function** was calculated. 
A **10-fold cross validation** method was computed to train and test the data and the **accuracy** was calculated. 
The model was built on Python.

**Feature engineer** was performed to transformed the raw data into a vector.

*Datasets*:
1. Political affiliation of a congressperson based on voting records of bills in the U.S. Congress. [Source](https://www.kaggle.com/devvret/congressional-voting-records).
2. Political affiliation of a person based on features such as income, gender, race, as well as opinions regarding Trump's administration, climate change, federal funding of scientific research, the use of vaccines on children, the total number of books read during last year, among others.[Source](https://www.kaggle.com/cardsagainsthumanity/pulse-of-the-nation?select=201709-CAH_PulseOfTheNation.csv).
