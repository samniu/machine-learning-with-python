# machine-learning-with-python
freeCodeCamp project


## cat and dog image classifier
1. import the required libraries.
2. download the data and set key variables.
3. create data(train, validation and test) generator use `ImageDataGenerator`

   `ImageDataGenerator` to read and decode the images and convert them into floating point tensors.

    `shuffle=False`

   `test_dir` subdirectory  or `flow_from_directory` expects a directory with a subdirectory by class.
   
5. create a model use the Keras Sequential model.
6. use `fit` method  to train and validate the network.
7. test the model.

## Book Recommendation Engine using KNN
1. load, extract data and import csv data into dataframes.
2. handle and clean data(remove and drop dumplicates).
3. merge and transform date to matrix format(KNN input param format).
4. train the KNN model
5. Query and get recommand data.
6. Test.
