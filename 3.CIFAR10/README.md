# CIFAR-10 Image Classification Project

This repository contains code and models for the CIFAR-10 image classification task using TensorFlow and Google Colab. The goal of this project is to explore different neural network architectures and techniques to achieve high accuracy on the CIFAR-10 dataset.

## Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is split into 50,000 training images and 10,000 testing images.

## Experiments

### Model 0: Conventional Neural Network
- Architecture: A conventional neural network
- Validation Accuracy: 47% after 20 epochs

### Model 1: Tiny VGG
- Architecture: Tiny VGG model
- Validation Accuracy: 62% after 20 epochs

### Model 2: Tiny VGG with Data Augmentation
- Architecture: Tiny VGG model with data augmentation layer
- Validation Accuracy: 43% after 20 epochs

### Model 3: Increased Model Size
- Architecture: Increased model size compared to Model 1
- Validation Accuracy: 61% after 40 epochs

### Model 4: Increased Model Size with Dropout
- Architecture: Same as Model 3, with additional dropout layers
- Validation Accuracy: 57% after 40 epochs

### Model 5: Complex Architecture with Various Techniques
- Architecture: Convolutional layers, pooling layers, dense layers, batch normalization, dropout, early stopping callback, reduce learning rate on plateau callback, data augmentation layer
- Validation Accuracy: 76.1% after 95 epochs "early stopped"

## Acknowledgments

This project was inspired by the CIFAR-10 dataset and built upon the foundations of TensorFlow and Google Colab. We acknowledge the open-source community for providing valuable resources and tools.

## Conclusion

Through these experiments, we've explored various architectures and techniques for image classification on the CIFAR-10 dataset. Each model represents a different approach to improving accuracy and combating overfitting. Feel free to experiment further and build upon these models to achieve even better results!

If you have any questions or suggestions, please feel free to reach out to us. Happy coding!
