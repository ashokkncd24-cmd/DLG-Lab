# Week 01 - Deep Learning Lab

## Program Title

Implementation of XOR using Artificial Neural Network and Backpropagation

## Aim

To implement a simple Artificial Neural Network using Python and NumPy to learn the XOR logic gate .

## Dataset Used

XOR dataset.

| Input 1 | Input 2 | Expected Output |
|---------|---------|-----------------|
| 0       | 0       | 0               |
| 0       | 1       | 1               |
| 1       | 0       | 1               |
| 1       | 1       | 0               |

No external dataset was used.

## Libraries Used

- NumPy

## Network Architecture

- Input layer: 2 neurons
- Hidden layer: 2 neurons
- Output layer: 1 neuron
- Activation function: Sigmoid
- Learning rate: 0.1
- Number of epochs: 10,000

## Algorithm

1. Initialize the XOR input data and expected output.
2. Initialize weights and biases randomly.
3. Perform forward propagation through the hidden layer.
4. Calculate the predicted output.
5. Calculate the error between expected and predicted output.
6. Perform backpropagation.
7. Update the weights and biases.
8. Repeat the process for 10,000 epochs.
9. Display the final predicted output.

## Result

The neural network successfully learned the XOR pattern. The predicted outputs were close to the expected outputs:

- 0 XOR 0 = 0
- 0 XOR 1 = 1
- 1 XOR 0 = 1
- 1 XOR 1 = 0

## Conclusion

A simple artificial neural network with one hidden layer was successfully implemented using NumPy. The network learned the non-linear XOR relationship using the backpropagation algorithm.
