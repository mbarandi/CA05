# CA05

This Python script uses the following packages and methods for performing k-Nearest Neighbors (k-NN) classification on a dataset of movies based on their genre information and IMDb ratings.

Packages Used
pandas: Used for data manipulation and analysis.
numpy: Used for numerical computing and arrays.
sklearn: Used for machine learning tasks, such as k-NN classification.


Methods Used
neighbors: A module from sklearn used for creating and training k-NN models.
KNeighborsClassifier: A class from the neighbors module used to implement the k-NN algorithm for classification.
NearestNeighbors: A class from the neighbors module used to find the k nearest neighbors for a given input.
fit(): A method used to train a model on a given dataset.
print(): A built-in Python function used to display output on the console.


Workflow
Import the necessary packages for the analysis, including pandas, numpy, and sklearn.
Assign the feature and class data to separate variables using pandas data frames.
Define and fit the k-NN model using the NearestNeighbors class from the sklearn.neighbors module.
Define the genre information and IMDb rating for a new movie.
Use the k-NN model to find the k most similar movies to the new movie based on their genre information and IMDb rating.
Print the k most similar movies to the console using the print() function.
