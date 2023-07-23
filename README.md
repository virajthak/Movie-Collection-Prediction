# Movie-Collection-Prediction

This is a Deep Learning project where a dataset contains data of movies, where our task is to predict the collection (revenue) the movie is going to make using variables such as expense, rating genre, etc. 
I have performed the following tasks.
* Import 'Movie Collection' csv files in data_x and data_y variables.
* Look at the shape and first five rows of the dataset to understand the data.
* Split the data into Train, Test and Validation set.
* Standardize the data.
* Create an ANN Model with two dense layers of 30 neurons each.
* Compile the model with loss="mean_squared_error", optimizer = keras.optimizers.SGD(lr=1 e-2) and metrics = ['mae']).
* Train the model for 100 epochs.
* Evaluat the model performance on the test set.
* Predict the values of the first 5 test records.
