# Food Vision Project: Classifying Food Images using Food101 Dataset

Welcome to the Food Vision Project! This Google Colab notebook showcases our journey in building and fine-tuning deep learning models for classifying food images using the Food101 dataset. Our primary goal is to distinguish various types of food items, with different experiments leading to improvements in accuracy.

## About the Project

In this Google Colab-based project, we focused on classifying food images using the Food101 dataset, which contains images of 101 different food categories. Our key achievements include:

- **Experiment 1: Pizza vs. Steak Classification:** We started by training a Tiny VGG architecture to distinguish between two popular categories: pizza and steak.

- **Experiment 2: 10-Class Food Classification:** We extended our model to distinguish between 10 food classes, including pizza, steak, and additional categories. 

- **Experiment 3: 100-Class Food Classification:** In our most ambitious experiment, we expanded the challenge to recognize 100 different food categories. This allowed us to demonstrate the scalability of our approach, achieving an accuracy of 74%.

Throughout our experiments, we leveraged the power of deep learning and made strategic decisions to optimize our models' performance.

## Models and Architecture

- **Base Architecture:** Our initial architecture was based on a Tiny VGG network, providing a solid starting point for our experiments.

- **Transfer Learning:** For improved performance, we explored transfer learning using two popular pre-trained models: EfficientNet and ResNetV2-50. After thorough experimentation, we found that EfficientNet was better suited for our use case, achieving the highest accuracy.

## Results and Insights

After a series of iterations and adjustments, we achieved a final accuracy of 74% on the Food101 dataset's 101 classes. Our experiments with different architectures, transfer learning, and model refinement allowed us to make informed decisions about the best approach for our food classification task.

## Notebook Structure

The Google Colab notebook in this project includes:

- Step-by-step code for loading and preprocessing the Food101 dataset.
- Implementation and training of our deep learning models for various experiments.
- Visualizations, analysis, and insights into the model's performance.

## Next Steps

- Further fine-tune the models to improve accuracy and generalization.
- Experiment with data augmentation techniques to enhance model robustness.
- Explore additional pre-trained models and architectures to potentially boost performance.
