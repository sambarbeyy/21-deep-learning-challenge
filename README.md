# 21-deep-learning-challenge

Step 1: Process the Data:

1. Read in the charity_data.csv to a Pandas DataFrame, and be sure to identify the following in your dataset:

*What variable(s) are the target(s) for your model?

*What variable(s) are the feature(s) for your model?

*For columns that have more than 10 unique values, determine the number of data points for each unique value.

*Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, Other, and then check if the binning was successful.

*Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.

*Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.

2. Step 2: Compile, Train, and Evaluate the Model

*Using your knowledge of TensorFlow, you’ll design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the features in the dataset.

*Create an output layer with an appropriate activation function.

*Check the structure of the model.

*Compile and train the model.

*Create a callback that saves the model's weights every five epochs.

*Evaluate the model using the test data to determine the loss and accuracy.

*Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity.h5.

