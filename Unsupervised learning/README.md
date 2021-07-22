
AIM: Classify vehicles into different types based on silhouettes which may be viewed from many angles. Used PCA in order to reduce dimensionality and SVM for classification.

Jupyter NB:VehicleClassification_Unsupervised learning
Dataset: vehicle-1.csv

Actions perform:

1.Basic EDA
2.Check for distribution of data.Perform feature engineering/ feature selection
3.Split into dependent/ independent variables. Split into train-test sets.
4.Train a Support vector machine using the train set and get the accuracy on the test set.
5.Perform K-fold cross validation and get the cross validation score of the model.
6.Use PCA from Scikit learn, extract Principal Components that capture about 95% of the variance in the data
7.Fit the model with original data and then principal components.
8.Print and comapre the performance of SVM model with PCA and without PCA.
