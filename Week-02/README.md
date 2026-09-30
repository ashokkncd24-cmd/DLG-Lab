# Week 02 - Deep Learning Lab

## Program Title

Implementation and Comparison of Batch Gradient Descent and Stochastic Gradient Descent

## Aim

To implement and compare Batch Gradient Descent and Stochastic Gradient Descent for training a neural network on the two-dimensional Moons dataset.

## Dataset Used

Two-dimensional Moons dataset generated using the `make_moons()` function from Scikit-learn.

- Number of samples: 400
- Noise: 0.20
- Random state: 1

## Libraries Used

- NumPy
- Scikit-learn

## Network Architecture

- Input layer: 2 neurons
- Hidden layer 1: 16 neurons
- Hidden layer 2: 16 neurons
- Output layer: 1 neuron
- Hidden layer activation: ReLU
- Output layer activation: Sigmoid
- Learning rate: 0.5
- Number of epochs: 200

## Algorithms Used

### 1. Batch Gradient Descent

The complete training dataset is used to calculate the gradients and update the weights once per epoch.

### 2. Stochastic Gradient Descent

The dataset is divided into mini-batches of 16 samples. The weights and biases are updated after processing each mini-batch.

## Procedure

1. Generate the Moons dataset.
2. Normalize the input features.
3. Initialize the neural network weights and biases.
4. Perform forward propagation.
5. Calculate gradients using backpropagation.
6. Update weights and biases using Batch Gradient Descent.
7. Calculate the Batch GD accuracy.
8. Reinitialize the network.
9. Train the network using mini-batch SGD.
10. Calculate the SGD accuracy.
11. Compare the results.

## Result

The neural network was trained using both Batch Gradient Descent and Stochastic Gradient Descent. The classification accuracy of both approaches was calculated and displayed in the output.

## Conclusion

Batch Gradient Descent and Stochastic Gradient Descent were successfully implemented for training a neural network on the Moons dataset. Both approaches were able to learn the classification pattern using backpropagation.
