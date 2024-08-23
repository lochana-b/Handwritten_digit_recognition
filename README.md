# Handwritten-Digit-Recognition

# Objective

This project aims to recognise handwritten digits (MNIST dataset) with a CNN using Keras.

# Key Design Considerations
This is a Multi-Class Classification problem (10 classes)

Language: Python
Deep Learning Package: Keras
Dataset: MNIST dataset available with Keras
Model: CNN

# Key Results
CNN based solution
Input (28x28x1 matrix) -> Conv(32 3x3 filters, relu) -> Maxpool(2x2) -> Conv(64 3x3 filters, relu) -> Maxpool(2x2) -> Conv(64 3x3 filters, relu) -> Flatten to a column vector for FCN -> FCN (64 outputs, relu) -> FCN (10 outputs, softmax)

Number of parameters = 93322

Training Accuracy = ~99.4%

Test Accuracy = ~99.3%

