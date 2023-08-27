# Image-classification-on-custom-dataset

This repository contains a comprehensive image classification project with the goal of classifying images of cats and dogs using the ResNet-50 architecture. The project includes several Jupyter Notebook files and a Telegram bot integration for monitoring training progress.

## Notebooks

### 1. For_Cat.ipynb
This notebook focuses on downloading images of cats from the Flickr API. It gathers a diverse dataset of cat images, which is essential for training an accurate image classification model.

### 2. For_Dog.ipynb
Similar to the previous notebook, this one is dedicated to downloading images of dogs from the Flickr API. By collecting a variety of dog images, the dataset becomes representative of real-world scenarios.

### 3. Siamese.ipynb
This notebook explores the Siamese network approach for image similarity and verification. Siamese networks are used for tasks like finding the similarity between two images and are often employed in face recognition systems.

### 4. Image-Classification_Model.ipynb
In this key notebook, the ResNet-50 architecture is employed to train an image classification model. The ResNet-50 model, pre-trained on ImageNet, is fine-tuned for classifying images of cats and dogs. The notebook also includes data preprocessing steps, model training, and evaluation.

## Telegram Bot Integration
The project integrates a Telegram bot that provides real-time updates on training progress. The bot sends notifications regarding accuracy, validation metrics, and loss during the training process. This feature enhances the convenience of monitoring the model's performance.

Feel free to explore the notebooks and adapt the code to your specific needs. The provided image classification model, based on ResNet-50, serves as a solid starting point for building accurate classifiers for other image datasets.


PS: If you find this project helpful, consider leaving a star ⭐ on this repository!
