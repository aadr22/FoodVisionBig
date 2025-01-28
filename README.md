# Food Vision Big: Food Image Classification on Food101 dataset

## Overview

Food Vision Big is a state-of-the-art deep learning model designed for food image classification, leveraging advanced Convolutional Neural Networks (CNNs). The project builds upon the Food101 dataset and aims to surpass the benchmark set by the 2016 DeepFood paper, achieving 83.9% top-1 accuracy, a significant improvement over DeepFood's 77.4%.

## Features

- Dataset: Utilizes the Food101 dataset, containing over 100,000 labeled images across 101 food categories.

Modeling Techniques:

- Pretrained CNN architectures for feature extraction.

- Fine-tuning specific layers for task-specific optimization.

- Mixed precision training for faster computations and reduced memory usage.

Data Augmentation: Implements resizing, normalization, and random transformations to improve model robustness.

Training Tools: Integrates TensorBoard visualization and learning rate schedulers for efficient training monitoring.

## Results

The model achieves:

- Top-1 Accuracy: 83.9% (a relative improvement of ~15% over DeepFood's benchmark).

- Demonstrates exceptional performance in classifying complex food images.

## How to Use

Clone this repository and ensure TensorFlow (v2.4+) is installed.

Run the provided notebook to:

Download and preprocess the Food101 dataset.

Train the CNN model using the provided architecture.

Evaluate the trained model on custom food images to classify them into one of 101 categories.
