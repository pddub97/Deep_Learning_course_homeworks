# Deep Learning course homeworks
Completed DL homeworks I did on the course at Skoltech

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

## Homework 2 (HW_2_part_1 and HW_2_part_2)
In this Homework I was training PyTorch skills.

### Part 1
Implemented:
* [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life) in PyTorch
*  Character recognicion problem on the notMNIST dataset. It consists of 10 letters and 14000 train samples. The solution was made in the low-level PyTorch functionalities.

### Part 2
Implemented:
*  Image multiclass classification problem on the Tiny ImageNet dataset (200 classes, 100K training images, 10K validation images). In comparison to the previous part, I was using all PyTorch functionalities. I used ResNet neywork architecture to solve this problem.

## Homework 3 ([Google Colab link](https://colab.research.google.com/drive/1xcfRKIbw6vGYuch0DBT7VjInhMoFsC31?usp=sharing))
Implemented, using UNet architecture:
* Image segmentation problem from the scratch on the dataset with colon-cancer cells images.
* Image denoising, where I increased the quality of an image 
* Image inpainting, here the blind spot of the image was filled in accordance with the rest of the image.
 Used Autoencoder and Variational Autoencoder to reconstruct face images
 
 
