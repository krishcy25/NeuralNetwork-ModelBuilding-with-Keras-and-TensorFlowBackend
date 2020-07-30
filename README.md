# NeuralNetwork-ModelBuilding-with-Keras-and-TensorFlowBackend


This repository focuses on building different versions of Neural Network Models with Keras that uses TensorFlow Backend.

The data used for building Neural Network is stored with in the repository "housepricedata.csv". The code to build/train the different versions of Neural Network is located in the repository as "NeuralNetwork_Keras_and_Tensorflow.ipynb"

![ke](https://user-images.githubusercontent.com/65406908/88950685-f8bd3980-d262-11ea-8c2a-ef8eea826e6b.jpeg)


## Keras is an open-source neural-network library written in Python. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML. Designed to enable fast experimentation with deep neural networks, it focuses on being user-friendly, modular, and extensible

3 different versions of Neural Networks were build in the code

## Model 1: Sequential Model
A Sequential model is appropriate for a plain stack of layers where each layer has exactly one input tensor and one output tensor.

## Model 2: Neural Network model with huge increase of hidden layers 
This model is built with increase in the number of hidden layers. With increase in the number of hidden layers, Model turned out to be overfitting. Overfitting of the model is observed in the code of the Notebook (with in Accuracy graph) where the Model performs very well on the Training data (with high accuracy) and performs worst on Validation data (with low accuracy when compared to Training data)

## Model 3: Adding Regularization to the Model 2(with increase of hidden layers) to reduce overfitting

Adding L2 regularization to same paramaters given to Model 2 thereby reducing the Overfitting in Model 2.

L2 regularization also referred to as Ridge regression

Ridge regression adds “squared magnitude” of coefficient as penalty term to the loss function

L2 Regularization adds the term Lambda and Lambda need to be choosen carefully.

L2 regularization forces the weights to be small but does not make them zero and does non sparse solution.
