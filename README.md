# Skin-Cancer-Detection
Skin Lesions Classifier

This repository provides an approach to building a Skin Cancer Detection Classifier using the concept of transfer learning. Transfer learning is a technique that involves taking a pre-trained deep neural network model, modifying it, and then using it as a starting point for a new task.

In this case, the repository uses pre-trained models like ResNet50, VGG11, DenseNet121, and InceptionV3, which are popular deep neural networks that have been trained on large datasets like ImageNet. These models have already learned to recognize a wide variety of features and patterns, making them excellent starting points for new classification tasks like skin cancer detection.

The approach involves modifying the pre-trained models to fit the new task of skin cancer detection. Specifically, the final layers of the pre-trained models are removed, and new layers are added that are specific to the skin cancer detection task. These new layers are then trained using a smaller dataset of skin cancer images.
