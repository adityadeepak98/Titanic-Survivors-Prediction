# Titanic-Survivors-Prediction

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we need to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

The data has been split into two groups:

training set (train.csv)
test set (test.csv)
The training set was used to build the machine learning model. For the training set, the outcome was provided (also known as the “ground truth”) for each passenger. The model is based on “features” like passengers’ gender and class. 

The test set was used to see how well the model performed on unseen data. For the test set, the ground truth for each passenger was not provided. I have predicted these outcomes. For each passenger in the test set, used the model I trained to predict whether or not they survived the sinking of the Titanic.

It also included gender_submission.csv, a set of predictions that assume all and only female passengers survive.
