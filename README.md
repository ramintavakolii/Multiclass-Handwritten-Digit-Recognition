# Handwritten Digit Recognition: Zero and One

In this exercise, we will use a neural network to recognize two handwritten digits, zero and one. This is a binary classification task.

## Data Set

The data set is a subset of the MNIST data set used for training the model. The subset of the dataset is as follows:

<p align="center">
  <img src="images/image1.PNG" alt="MNIST Subset" width="400">
</p>

## Model Representation

The neural network used in this assignment is shown in the figure below. It has three dense layers with sigmoid activations.

- Recall that our inputs are pixel values of digit images.
- Since the images are of size \(20 \times 20\), this gives us 400 inputs.

<p align="center">
  <img src="images/image2.PNG" alt="Neural Network Model" width="600">
</p>

## Implementation Details

We build our own dense layer using NumPy. This can then be utilized to build a multi-layer neural network. Additionally, we use TensorFlow packages for comparison. 

We will see predictions from both the NumPy model and the TensorFlow model.

<p align="center">
  <img src="images/image3.PNG" alt="Model Comparison" width="600">
</p>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the contributors and developers of the tools and libraries used in this project.