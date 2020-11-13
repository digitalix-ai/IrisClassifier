# IrisClassifier
Machine Learning model for Iris flower types classification

A program, which uses the sklearn Python library, to select and train a ML model to do classification of the 3 different Iris flower types.
The 3 types differentiate by 4 different characteristics, represented as 4 different numbers in the data, or an array of 4 numbers for every
iris flower. The 4 features of the flowers represented are the length and the width of the sepals and petals, in centimeters.
The K Nearest Neighbors (KNN) algorithm is used in the program. The iris flower dataset is readily used from the sklearn library. The data is
split into training and testing parts. The KNN algorithm is being trained on the training data and then tested on the testing data set.

The program is contained in the Iris.ipynb file, a Jupyter Notebook.

Then, using the joblib library, the trained ML algorithm (model) is saved on a separate file, called mlbrain.joblib. The saved model can then
be used for future predictions, including new examples of iris flowers, not contained in the data.
