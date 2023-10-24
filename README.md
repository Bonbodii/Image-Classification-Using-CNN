# Image-Classification-Using-CNN

## Table of Contents

1. [Task Introduction](#task-introduction)
2. [Dataset](#dataset)
3. [Evaluation Metrics](#evaluation-metrics)


## Task Introduction

### Image Classification
The primary task in this project is to perform image classification using convolutional neural networks (CNNs). Your goal is to classify images into one of the 11 predefined classes.

## Dataset

### Overview
- The dataset is collected from the food-11 dataset, which has been divided into 11 classes.
- Training set: 10,000 labeled images
- Validation set: 3,643 labeled images
- Testing set: 3,000 unlabeled images

## Evaluation Metrics

- The primary evaluation metric for your model is the accuracy on the testing set.

### Q1. Augmentation Implementation (2%)
- Implement augmentation by finishing the `train_tfm` function in the code with an image size of your choice.
- Copy your `train_tfm` code and paste it onto Gradescope, and explain the effects of the transformations you report.
- Your `train_tfm` must be capable of producing 5+ different results when given an identical image multiple times.

### Q2. Visual Representations Implementation (2%)
- Visualize the learned visual representations of the CNN model on the validation set by implementing t-SNE on the output of both top and mid layers (You need to submit 2 images).
- Briefly explain your results of the t-SNE visualization.
