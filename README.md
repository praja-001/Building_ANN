# Building_ANN
It is using Keras (Using TensorFlow Backend). Steps to be followed are:

Building ANN -Import important libraries (Numpy, Matplotlib, Pandas) -Dataset -Encoding Categorical Data (if needed) -Splitting Data into Train and Test -Feature Scaling

Building ANN -Import Keras and Models (Sequential, Dense)

Initialising ANN (Two ways: Defining as a sequence of layers or defining a graph) -Creating object from Sequential class (classifier) - Adding layers (input and hidden)

Adding final layer

Compiling ANN (SGD applied)

Choosing the number of epochs -Fitting the ANN to training set

Making predictions (initialising the threshold)

Confusion Matrix and Accuracy

The file contains the evaluation, improvement of the ANN and parameter tuning.

K-fold Cross Validation is used for evaluating the ANN
Dropout regularisation is implemented.
Grid search with cross validation is used to tune the hyperparameters.
