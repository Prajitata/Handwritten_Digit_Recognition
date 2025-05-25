# Handwritten_Digit_Recognition
This repository contains a simple deep learning model built using TensorFlow and Keras. The notebook demonstrates how to classify handwritten digits from the MNIST dataset using a neural network with a single hidden layer.
## Model Overview

- **Input Layer**: 784 units (flattened 28x28 pixel image)
- **Hidden Layer**: 128 neurons, ReLU activation
- **Output Layer**: 10 neurons, softmax activation
- **Loss Function**: Categorical Crossentropy
- **Optimizer**: Adam
- **Evaluation Metric**: Accuracy

## Project Highlights

- **Framework**: TensorFlow/Keras
- **Dataset**: MNIST — 70,000 images of handwritten digits (28x28 pixels)
- **Architecture**: Fully connected (Dense) neural network with one hidden layer
- **Training Results**: The model achieved a high accuracy on the test set, and the loss steadily decreased with each epoch, indicating effective learning.

## Training Performance: Loss Reduction

During training, the model showed a **consistent decrease in loss** and **increase in accuracy** over each epoch, confirming that it was learning effectively. The loss curve typically followed a downward trend like this:

- **Epoch 1**: Loss ~0.35, Accuracy ~88%
- **Epoch 5**: Loss ~0.15, Accuracy ~95%
- **Final Epoch**: Loss ~0.09, Accuracy ~97%

## This digit classification model has practical use in optical character recognition (OCR), automated check processing, reading handwritten documents, and number plate detection. It also serves as a foundational example for building more advanced image classification systems in real-world applications.

