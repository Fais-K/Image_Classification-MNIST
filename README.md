# Image Classification - MNIST

### Image classification on MNIST dataset.

You may find two 'ipynb' files in the repository i.e mnist_dnn_torch.ipynb and mnist_cnn_tf.ipynb. Each file does the same work but using different methods and frameworks.

1. **mnist_dnn_torch.ipynb**

This is the pure DNN based image classification model trained and tested on MNIST dataset using the PyTorch framework.

Layers (including input and output): 3 (784, 512, 10)

Dropout: After layer 2 (p=0.2)

Epochs: 30

Validation Accuracy: 98%

2. **mnist_cnn_tf.ipynb**

This is a CNN based image classification model trained and tested on MNIST dataset using the TensorFlow framework.

Convolutions: 3 (filters -> 32, 64, 64) (kernel -> 3, 3, 3)

Batch Normalization: after convolution 1

MaxPool2D: after convolutions 2 and 3

Layers (including input and output): 3 (512, 128, 10)

Dropout: After layer 1 and 2 (p=0.2, p=0.1)

Epochs: 10

Validation Accuracy: 99.10%

