# CIFAR-10 Object Recognition using CNN

A deep learning project where I built a Convolutional Neural Network (CNN) to classify 10 different types of objects from the CIFAR-10 dataset using PyTorch.

## What This Project Does

I trained a CNN model that can identify 10 different objects in color images: airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. This project helped me understand how neural networks handle more complex, real-world images compared to simple digit recognition.

## Dataset

I used the **CIFAR-10 Dataset** which contains:
- 50,000 training images across 10 object categories
- 10,000 test images
- Each image is 32×32 pixels in RGB color
- 10 classes: airplane, car, bird, cat, deer, dog, frog, horse, ship, truck

## Model Architecture

I built a **Convolutional Neural Network** with:
- 3 convolutional layers for hierarchical feature extraction
- 3 max pooling layers for spatial dimension reduction
- Dropout layer (50%) to prevent overfitting
- 2 fully connected layers for final classification
- Output layer with 10 neurons (one for each object class)

The model processes 32×32 RGB images through multiple convolutional layers, progressively extracting more complex features before making final predictions.

## Results

After training the model for 20 epochs, I achieved approximately **70-80% accuracy** on the test dataset. The model successfully classifies real-world objects with reasonable precision, demonstrating the challenges of color image classification compared to simpler datasets like MNIST.

## Key Learnings

Through this project, I learned:
- Working with RGB color images in PyTorch
- Building deeper CNN architectures for complex image classification
- Handling multi-class classification problems
- The importance of dropout and regularization techniques
- Differences between simple and complex image recognition tasks

