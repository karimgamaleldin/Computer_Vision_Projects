# Transfer Learning-Based Image Segmentation and Cat-Dog Classification

This repository contains the code and resources for a project that combines image segmentation and binary classification to identify and locate cats and dogs in images. We utilized transfer learning on the Oxford IIT dataset to build two models: one for image segmentation and another for classifying whether an image contains a cat or a dog. These models were then tested on a custom photo dataset.

## Overview

- **Segmentation Model**: We employed a U-Net inspired architecture for image segmentation. This model identifies the precise positions of cats and dogs in images.

- **Classification Model**: For binary classification (cat or dog), we used an EfficientNet-based model. This model predicts whether the image contains a cat or a dog.

## Dataset

- We used the [Oxford IIT Pet Dataset](http://www.robots.ox.ac.uk/~vgg/data/pets/) for training and evaluation.
