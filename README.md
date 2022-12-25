# DeepLearning-Facial-expression-recognition
Identification of facial expressions using custom and pretrained models
# Contents
- [Overview](###Overview)
- [Dataset](###Dataset)
- [Models](###Models)
- [Summary](###Summary)
### Overview
A ResNet model that detects the emotions Sad, Neutral, Happy, Fear, Disgust, Surprise, Angry from input facial images.
### Dataset
The dataset used was downloaded from kaggle competitions  
Link: https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset
### Models
ResNet9: Custom residual network for image classification  
ResNet34: A residual network model trained on ImageNet dataset.
### Summary
Two models ResNet9 and Resnet34 are used with different hyperparameters is used for Facial expression recognition (image classification problem).It is observed that different models tanked at an accuracy of 63-67%.

The accuracy hence can be improved by increasing size of dataset and the quality of dataset and little more finetuning of hyperparameters.


