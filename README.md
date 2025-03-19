

# CIFAR-100 Image Classification with PyTorch

This repository focuses on classifying images from the **CIFAR-100 dataset** using convolutional neural networks (CNNs) built with the PyTorch library. The CIFAR-100 dataset is a challenging benchmark for image classification, containing 100 diverse classes grouped into 20 superclasses.

## Dataset Overview
- **Training and Testing Images**: Each class contains 500 training images and 100 testing images.
- **Classes and Superclasses**: The dataset includes 100 fine-grained classes, further grouped into 20 broader superclasses.
- **Labeling**:
  - *Fine labels*: Specify the exact class of the image.
  - *Coarse labels*: Indicate the superclass to which the image belongs.

## Project Objectives
1. **Dataset Division**: The training dataset is divided into two subsets:
   - A sub-training set.
   - A validation set (20% of the training data).
2. **Fine Label Prediction**: The model is designed to predict the *fine labels* (class) rather than the *coarse labels* (superclass).
3. **Model Experimentation**:
   - Experiment with various activation functions, optimizers, hyperparameters, and architectures.
4. **Model Selection**:
   - Identify the top three models based on performance on the validation set.
5. **Full Training**:
   - Retrain the top three models using the entire training dataset.
6. **Accuracy Testing**:
   - Evaluate and compare test accuracy for each model.
7. **Benchmarking**:
   - Compare model performance against others on the CIFAR-100 leaderboard (considering only models without additional training data).
8. **Reporting**:
   - Provide a detailed report covering:
     - Activation functions, optimizers, hyperparameters, and architectures used.
     - Test accuracy results.
     - Benchmarking outcomes.
     - Total number of parameters for each model.

