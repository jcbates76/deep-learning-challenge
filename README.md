# Deep Learning Challenge

## Background
The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful.  

## Step 1: Preprocess the Data
* Read in the charity_data.csv file into Pandas.
* Drop the EIN and NAMES columns.
* For those columns with more than 10 unique values, determine the number of data points for each unique value.  
* Use the number of data points for each unique value to pick a cutoff point to bin "rare: categorical variables together in a new value OTHER, and then check if the binning was successful.
* Use pd.get_dummies() to encode categorical variables.  

## Step 2: Compile, Train, and Evaluate the Model
* Create a neural network model by assigning the number of input features and nodes for each layer using Tensorflow Keras.
* Create the first hidden layer and choose an appropriate activation function.
* If necessary, add a second hidden layer with an appropriate activation function.
* Create an output layer with an appropriate activation function.
* Check the structure of the model.
* Compile and train the model.
* Create a callback that saves the model's weights every 5 epochs.
* Evaluate the model using the test data to determine the loss and accuracy.  
* Save and export the results to an HDF5 file, and name it AlphabetSoupCharity.h5.  

## Step 3: Optimize the Model
* Adjust the input data to ensure that there are no variables or outliers that are causing confusion in the model.  

## Step 4: Write a Report on the Neural Network Model
