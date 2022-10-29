# Titanic_Machine_Learning_from_Disaster
This repository presents my submission in the Titanic: Machine Learning from Disaster, Kaggle Competition.
In this competition, the goal is to perform a 2-label classification problem: predict which passengers survived the tragedy.
Kaggle offers two datasets. One training (the labels are known) and one testing (the labels are unknown). The goal is to submit a file with our predicted labels saying who survived or not.

We have access to a bunch of 9 features (numerical, text, categorical). The big challenge with this competition is the size of the data we have. The training set is composed of only 891 samples. The testing set is composed of 418 samples.
Therefore, the main issue is to design an algorithm which generalizes enough in order to avoid over-fitting. To do so, a bunch of features is generated. Then, an ensemble modeling method with voting is used in order to get the most generalized model.
