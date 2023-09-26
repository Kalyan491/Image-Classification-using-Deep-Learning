# Assignment 1: Image Classification

## Table of Contents

1. [Feature Extraction + k-NN](#feature-extraction--k-nn)
   - [Implementation](#implementation)
   - [Results](#results)
2. [Transfer Learning with ResNet18](#transfer-learning-with-resnet18)
   - [Implementation](#implementation-1)
   - [Results](#results-1)
3. [Neural Network from Scratch](#neural-network-from-scratch)
   - [Implementation](#implementation-2)
   - [Results](#results-2)
4. [Comparison Between Models](#comparison-between-models)
5. [Observations and Challenges](#observations-and-challenges)

## Feature Extraction + k-NN

### Implementation

- Implemented feature extraction using a pre-trained ResNet-18 model.
- Data preprocessing, transformation, and loading.
- Feature extraction from the last layer.
- Saving features for k-NN classification.

### Results

- Detailed results of k-NN classification.
- Example images and their classifications.

## Transfer Learning with ResNet18

### Implementation

- Preprocessed and normalized images using ImageNet mean and standard deviation.
- Split the training data into train and validation sets.
- Loaded pre-trained ResNet-18 model.
- Fine-tuned the model with a custom classification layer.
- Trained with different optimizers and learning rates.

### Results

- Test accuracy on test data.
- Validation accuracy during training.
- Classification report and observations.

## Neural Network from Scratch

### Implementation

- Preprocessed and normalized images using training data mean and standard deviation.
- Split the training data into train and validation sets.
- Designed a custom convolutional neural network (CNN) from scratch.
- Implemented data loading and training with cross-entropy loss.
- Explored different CNN architectures.

### Results

- Test accuracy on test data.
- Validation accuracy during training.
- Classification report and observations.

## Comparison Between Models

- Compared k-NN, fine-tuning, and custom CNN approaches.
- Analyzed differences in accuracy and computational requirements.
- Discuss the impact of hyperparameters.

## Observations and Challenges

- Summarized observations and challenges faced during the assignment.
- Discussed key learnings from each approach.

---

This README provides a structured format for your GitHub repository, making it easier for users to understand the contents of your image classification assignment and access relevant information and results.
