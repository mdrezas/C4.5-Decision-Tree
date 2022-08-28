# Decision-Tree
Train a decision tree to predict whether a person makes over $50K a year based on the UCI Adult Census Income dataset.

This database contains 48842 instances. Each instance is described in terms of 14 attributes. The last
column attribute named \income" is the binary outcome to predict (i.e., > 50K or otherwise).

Notice there are both numeric and discrete attributes.

Tasks:

The data set can be downloaded from the website https://www.kaggle.com/
uciml/adult-census-income. After downloading the data set, please split it into
training set (70%), validation set (10%) and test set (20%).

Implement the C4.5 decision tree algorithm described in class. Your implementa-
tion should let user determine when to stop the recursive splitting.

Run your algorithm on the training set to learn a decision tree using the following
cut-off values = 0:2; 0:4; 0:6; 0:8 in pseudocode I covered in class. Plot the
training error for each cut-off Hint: you can use training set to grow
the tree and use validation set to calculate training error.

Test your decision trees on the test set. And plot test error together with training
error for each tree you train. What is your conclusion?
