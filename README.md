# Deep-Learning-and-Neural-networks-with-keras
Build a regression model using the Keras library to model the same data about concrete compressive strength.
Part A: 
Build a baseline model 
Used the Keras library to build a neural network with the following:
- One hidden layer of 10 nodes, and a ReLU activation function
- Used the adam optimizer and the mean squared error  as the loss function.
1. Randomly splited the data into a training and test sets by holding 30% of the data for testing. With the use of
train_test_split helper function from Scikit-learn.
2. Trained  the model on the training data using 50 epochs.
3. Evaluated the model on the test data and compute the mean squared error between the predicted concrete strength and the actual concrete strength. You can use the mean_squared_error function from Scikit-learn.
4. Repeat steps 1 - 3, 50 times, i.e., create a list of 50 mean squared errors.
5. Reported the mean and the standard deviation of the mean squared errors.
   
Part B: 
Normalized the data 
Repeated Part A but used a normalized version of the data. Normalized the data by subtracting the mean from the individual predictors and dividing by the standard deviation.
Compared the results how does the mean of the mean squared errors compare to that from Step A?


Part C: Increased the number of epochs
Repeated Part B but used 100 epochs this time for training.
Compared the results how does the mean of the mean squared errors compare to that from Step B?

Part D: Increased the number of hidden layers 
Repeated part B but used a neural network with the following instead:
- Three hidden layers, each of 10 nodes and ReLU activation function.
Compared the results of how does the mean of the mean squared errors compare to that from Step B?
