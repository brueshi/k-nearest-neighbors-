K-Nearest Neighbors (KNN):
K-Nearest Neighbors is a simple but powerful algorithm for both classification and regression. It classifies new data points based on the majority vote of its k nearest neighbors in the training data.

Explanation:

We import the KNeighborsClassifier class from the sklearn.neighbors module.
An instance of the KNeighborsClassifier class is created, specifying the number of neighbors (k) using the n_neighbors parameter.
The classifier is trained on the training data using the fit method.
Finally, we make predictions on the test data using the predict method and store the predicted values in y_pred.
