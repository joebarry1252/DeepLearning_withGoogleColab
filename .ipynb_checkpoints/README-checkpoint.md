# Unit 14 - Deep Learning Homework

In this activity, I use deep learning neural networks to forecast Bitcoin closing prices. The first model uses FNG ("Fear and Greed") indicators to predict prices; the second takes a window of several closing prices to predict future closing prices.

## Prepare data for training and testing\

Use the starter code as a guide to create a Jupyter Notebook for each RNN. The starter code contains a function to create the window of time for the data in each dataset.

For the Fear and Greed model, you will use the FNG values to try and predict the closing price. A function is provided in the notebook to help with this.

For the closing price model, you will use previous closing prices to try and predict the next closing price. A function is provided in the notebook to help with this.

Each model will need to use 70% of the data for training and 30% of the data for testing.

Apply a MinMaxScaler to the X and y values to scale the data for the model.

Finally, reshape the X_train and X_test values to fit the model's requirement of samples, time steps, and features.


## Build and train the LSTM models

In each Jupyter Notebook, create the same custom LSTM RNN architecture. In one notebook, you will fit the data using the FNG values. In the second notebook, you will fit the data using only closing prices.

Use the same parameters and training steps for each model. This is necessary to compare each model accurately.


## Evaluate each model's performance

Finally, use the testing data to evaluate each model and compare the performance.