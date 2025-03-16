# SE-CNN for Efficient MNIST Digit Recognition
 SE-CNN-MNIST-Recognition: This project introduces an enhanced Squeeze-and-Excitation Convolutional Neural Network (SE-CNN) designed for efficient handwritten digit recognition on the MNIST dataset. Traditional CNNs suffer from reduced accuracy (e.g., dropping from 98.32% to 86.73% with 50% data) due to their dependency on large datasets and information loss during pooling. By integrating SE blocks into a baseline CNN with three convolutional layers (32, 64, 64 filters), this SE-CNN recalibrates features to maintain high accuracy—achieving ~99.2% on the full MNIST dataset and ~95% on just 50% of the data—with a low computational cost (~0.7G FLOPs). The repository includes implementation code, a detailed case study, and comprehensive documentation, supporting training, evaluation, and prediction on external images. Ideal for resource-constrained applications like IoT, this project demonstrates a robust, data-efficient alternative to conventional models, rivaling advanced architectures like CapsNet with less complexity.
# SE-CNN-MNIST-Recognition

An efficient Squeeze-and-Excitation Convolutional Neural Network (SE-CNN) for MNIST digit recognition, achieving ~99.2% accuracy on full data and ~95% on 50% data.

## About
This project enhances traditional CNNs by integrating SE blocks to improve feature recalibration, reducing data dependency while maintaining high accuracy. It includes code, a case study, and documentation for training, evaluation, and external image prediction.

## Features
- SE-CNN model with 3 Conv2D layers and SE blocks
- High accuracy (>95%) with reduced MNIST data
- Visualization of training history and predictions
- Support for external image prediction (e.g., handwritten digits)

## Prerequisites
- Python 3.8+
- TensorFlow 2.x
- NumPy, Matplotlib, OpenCV
- Jupyter Notebook

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SE-CNN-MNIST-Recognition.git
   cd SE-CNN-MNIST-Recognition
