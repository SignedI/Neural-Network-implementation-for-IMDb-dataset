# Neural-Network-implementation-for-IMDb-dataset

In this project, I try to carry out the sentiment analysis of the IMDb dataset using neural networks.

I have used keras library in python to make the neural network and train the model further. I further use scikit-learn to measure the accuracy of the model in making predictions.

The IMDb dataset contains 50,000 reviews of movies, which are classifed as 1 (positive) or 0 (negative) in the dataset. The reviews can be said to be quite polar. We split the data and use 50% of the reviews for training the model and the rest 50% of the data for testing the model.

While training the data, we first vectorize the data and try to find out the frequency of the words being used. After that, we will form our neural network model and then train our model using the given training dataset. Then we make predictions finally and output the accuracy with which we were able to make our predictions.
