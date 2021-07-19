# Deep learning course homeworks
Completed DL homework I did on the course at Skoltech

## Homework 1 (HW_1)
1. Did the matrix differentioation task (github doesn't render LaTeX code from .ipynb)
2. Learned the concept of the  Module class, forward and backpropagation passes and the Sequential container class for the chains of modules.

3. Implemented myself in numpy and/or learned:

  * The most popular layers: Fully-connected (Linear), SoftMax, LogSoftMax, Batch-normalization and Dropout.
  * Activation functions: ReLU, Leaky ReLU, ELU, SoftPlus
  * Criterions: MeanSquaredError criterion, Negative LogLikelihood criterion (both numerically stable and unstable)
  * Optimizers: SGD optimizer with momentum, Adam optimizer
  * Convolution Neural Netork related layers: Convolutional (like Conv2d in PyTorch), Max Pooling (like MaxPool2d in PyTorch), Flatten (reshapes the input to the 1-dimension output)

4. Trained:
  * Digit classification Linear layer - based network on the MNIST dataset. Compared different activation functions and optimizers. Showed the effect of the Batch normalization and Dropout layers.
  * CNN network for the same task.
