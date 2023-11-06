# Handwritten Digit Recognition in C++

Welcome to my Handwritten Digit Recognition C++ project from HUJI course 67315 (2022) PROGRAMMING WORKSHOP IN C & C++.
software is designed to recognize handwritten digits between 0 and 9 using a neural network model in C++.

<p>
  <img src="https://github.com/YarinBeni/HUJI-CPP--Digit-Recognition-Project/blob/main/model_example_image.png?raw=true" width="650" height="250" alt="CNN Architecture for Digit Recognition" />
</p>
<p>
  <em>Figure: Convolutional Neural Network (CNN) architecture used for digit recognition with handwritten datasets. The model's structure is tailored to interpret the nuances of human handwriting, enabling precise digit classification. Special thanks to the insights from <a href="https://medium.com/@himanshubeniwal/handwritten-digit-recognition-using-machine-learning-ad30562a9b64">this article</a> on machine learning-based handwritten digit recognition.</em>
</p>


## How it works
We have trained a neural network model on a large dataset of images of handwritten digits to accurately recognize digits with an accuracy of around 96%.
The model consists of four layers and takes in weights and offsets for each layer as input.
I recommend watching the following video From 3Brown1Blue detailing the structure of a neural network and how it can be implemented using linear algebra:
https://www.youtube.com/watch?v=aircAruvnKk

## Requirements
To run our software, you will need a C++ compiler and the following dependencies:
Eigen library for linear algebra operations

## Usage
To use this software, simply run the following command:
./mlpnetwork w1 w2 w3 w4 b1 b2 b3 b4
Where w1, w2, w3, and w4 are the paths to the weight files for each layer and b1, b2, b3, and b4 are the paths to the offset files for each layer.

The software will then prompt you for the path to an image file containing a handwritten digit.
When a result is received, the software will print the image, the digit that the network recognized, and the probability of the identification.
To exit the software, enter q at the prompt.

## Credits
This project was developed by Yarin Benizri. I would like to thank the creators of the MNIST dataset for providing the training data for our model.



I hope you find our software useful! If you have any questions or suggestions, please feel free to contact us.
