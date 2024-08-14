# Hand Gesture Sign Recognition

This project implements a neural network using TensorFlow to classify images of hand signs. The model is trained to recognize different hand signs from a dataset of images. The goal is to build a robust model that can accurately classify images into one of several categories.




## Dataset
The dataset used in this project is a subset of the images of hand signs. It is divided into training and test sets:

Training Set: Contains images used to train the model.

Test Set: Contains images used to evaluate the model’s performance.

Image Details: Each image is of size 64x64 pixels and has 3 color channels (RGB).

Labels: The dataset includes labels for each image, indicating the hand sign category (0-5).
## Key Steps
Data Loading: Load the training and test datasets using the h5py library.

Data Preprocessing: Normalize the images and convert labels to one-hot encoding.

Model Initialization: Initialize the neural network parameters using the Glorot initializer.

Forward Propagation: Implement the forward propagation steps with linear and ReLU activations.

Loss Computation: Compute the total loss using categorical cross-entropy.

Model Training: Train the model using the Adam optimizer and track the training and test accuracy.

Evaluation: Evaluate the model’s performance on the test set and visualize the results.
## Conclusion
This project successfully demonstrates the use of TensorFlow to build a neural network for hand gesture sign recognition1. By leveraging a well-structured dataset and implementing effective preprocessing techniques

The use of multiple layers and the Adam optimizer ensures efficient training and performance
