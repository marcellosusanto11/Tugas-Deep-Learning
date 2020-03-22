# Predict Cloth Type
First assignment of `MA4072 Deep Learning` Class
<br>Collaboration with : Suparjo

This experiment purpose is to learn more about the mechanic of fully-connected neural network. Because of that we will not use a popular package such as Keras to build our ANN model. Instead we will make our own NeuralNetwork class with all the component code from scratch. 

<br> We have 60000 training dataset and 10000 testing dataset consisting of 28x28 pixel image of clothes with the label representing the clothes type. We want to build an ANN model that will receive image as an input and predict what type of cloth for each image. We will use 4 combination of activation function and loss function. For each combinaton we will find the optimal learning rate, scaler, and the option to increase the total of neuorn in each hidden layer or increase the total of the hidden layer if its necessary


# Predict BBCA Stock
Second assignment `of MA4072 Deep Learning` Class 
<br>Collaboration with : Suparjo

This experiment purpose is to learn more about the mechanic of Recurrent Neural Network. Because of that we will not use a popular package such as Keras to build our RNN model. Instead we will make our own RecurrentNeuralNetwork class with all the component code from scratch.

We are using the historical OHLC stock data of BBCA from January 2017 to December 2019. Before modelling we will preprocess this data to a `time-step` format and normalize the value. Then we will build 2 model of RNN with the first one using sigmoid as output layer activation funtion and the second one don't use the activation function. Since this is a regression task if we using the first model we will have to transform the output value into the stock value again using the inverse scaler. The objective of this assignment is to gain the best parameter for the RNN model


# Predict Digit
Third assignment `of MA4072 Deep Learning` Class 
<br>Collaboration with : Suparjo

This experiment purpose is to learn more about the impact of implementing optimizer in a multi layer perceptron model. We will make the code for the optimizer from scratch to fully understand how the optimizer work. We are using the 8x8 pixel image data that consist of a digit range from 0 to 9. The model we use are the same model as the first assignment
