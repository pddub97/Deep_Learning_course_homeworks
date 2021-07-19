# Deep learning course homeworks
Completed DL homework I did on the course at Skoltech

## Homework 1 (HW_1)
* Did the matrix differentioation task (github doesn't render LaTeX code from .ipynb)
* Learned the concept of the  Module class (with forard and backpropagation passes) and Sequential container class (for the chains of modules).

* Implemented myself and/or learned (in numpy):

  1. The most popular layers: Fully-connected (Linear), SoftMax, LogSoftMax, Batch-normalization and Dropout.
  2. Activation functions: ReLU, Leaky ReLU, ELU, SoftPlus
  3. Criterions: MeanSquaredError (MSE) criterion, Negative LogLikelihood criterion (both numerically stable and unstable)
  4. Optimizers: SGD optimizer with momentum, Adam optimizer
  5. Convolution Neural Netork related layers: Convolutional (like Conv2d in PyTorch), Max Pooling ( like MaxPool2d in PyTorch), Flatten (reshapes the input to the 1-dimension output)

* Trained:
  1. Digit classification Linear layer - based network on the MNIST dataset. Compared different activation functions and optimizers. Showed the effect of the Batch normalization and Dropout layers.
  2. CNN network for the same task.
