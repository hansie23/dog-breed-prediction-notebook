# Multi-class Dog breed prediction project

## Data
The data is used from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data

## Features
Some information about the data:
* There are 120 dog breeds (this means there are 120 different classes).
* There are around 10000+ images in the training set (these images have labels).
* There are around 10000+ images in the test set (these images have no labels).

## Model URL
The URL of the model we want to use from TensorFlow Hub - https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/5

## Workflow
- Get data ready (turn into Tensors) and create batches
- Design and build model
- Create callbacks
- Train model
- Make predictions
- Unbatchify batched data
- Verify predictions