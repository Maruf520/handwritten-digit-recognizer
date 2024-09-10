# handwritten-digit-recognizer neural-netwrk

# MNIST Handwritten Digit Recognition

This project demonstrates how to load the MNIST dataset, which contains hand-written digit images (0-9), each of size 28x28 pixels. The dataset is split into training and test sets and is commonly used for building and evaluating machine learning models.

## Dataset Overview

- The MNIST dataset consists of:
  - **60,000 training images**
  - **10,000 test images**
- Each image is a grayscale image of size **28x28 pixels** representing a digit from **0 to 9**.

## Loading the MNIST Dataset

The dataset can be easily loaded using the `load_data()` method from libraries such as TensorFlow.

### Code Example

Here’s how you can load the MNIST dataset using TensorFlow:

```python
from tensorflow.keras.datasets import mnist

# Load the MNIST dataset
(train_images, train_labels), (test_images, test_labels) = mnist.load_data()

# Check the shape of the dataset
print(train_images.shape)  # Output: (60000, 28, 28)
print(test_images.shape)   # Output: (10000, 28, 28)
```

This ensures that
