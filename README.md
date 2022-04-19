# Course_Project_Practical_Machine_Learning

This is the course project for the Coursera course Practical Machine Learning. 

We will use data from accelerometers on the belt, forearm, arm, and dumbell of six participants in this experiment to forecast how they will perform the workout. In the training set, this is the "classe" variable. On the training set, we use k-folds cross validation to train four models: Decision Tree, Random Forest, Gradient Boosted Trees, and Support Vector Machine. The accuracy and out of sample error rate are then calculated using a validation set randomly selected from the training csv data. Based on those numbers, we decide on the best model, and use it to predict 20 cases using the test csv set.


