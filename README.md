# Handwritten-Digit-Recognition-Using-Convolutional-Neural-Network
## Problem
In this problem we will be using MNIST dataset. The MNIST dataset is an acronym that stands for the Modified National Institute of
Standards and Technology dataset. It is a dataset of 60,000 small square 28×28 pixel
grayscale images of handwritten single digits between 0 and 9. 
The MNIST handwritten digit classification problem is a standard dataset used in computer
vision and deep learning. Although the dataset is effectively solved, it can be used as the
basis for learning and practicing how to develop, evaluate, and use convolutional deep
learning neural networks for image classification from scratch. 
The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9,
inclusively. It is a widely used and deeply understood dataset and, for the most part, is
“solved.” Top-performing models are deep learning convolutional neural networks that
achieve a classification accuracy of above 99%, with an error rate between 0.4% and 0.2% on
the hold out test dataset. Example of MNIST data set given below;
<br/><br/>
![image](https://user-images.githubusercontent.com/45359225/189692508-c4ce44a1-e84b-44df-9b3f-61af4c22e46d.png)

## Project Description
A simple artificial neural network (ANN) has an input layer, an output layer and some hidden
layers between the input and output layer. CNN has a very similar architecture as ANN.
There are several neurons in each layer in ANN. The weighted sum of all the neurons of a
layer becomes the input of a neuron of the next layer adding a biased value. In CNN the layer
has three dimensions. Here all the neurons are not fully connected. Instead, every neuron in
the layer is connected to the local receptive field. A cost function generates in order to train
the network. It compares the output of the network with the desired output. The signal
propagates back to the system, again and again, to update the shared weights and biases in
all the receptive fields to minimize the value of cost function which increases the network’s
performance. The goal of this project is to observe the influence of hidden layers of a CNN
for handwritten digits.
<br/><br/>
![image](https://user-images.githubusercontent.com/45359225/189693046-2f509c8c-6bb4-4437-b113-bbf1cac49702.png)

