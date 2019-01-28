# dog_breed_cnn_implementation
CNN project to recognize dog breeds

## Project Overview

In this project for the Udacity Machine Learning Nanodegree, I implemented a CNN with AWS GPU to classify dog breeds or the most resembling dog breed among 133 available breeds when given as input an image of either a dog or a human. I used two pre-trained models `ResNet-50` to detect dogs and `OpenCV-Harr Cascades` to detect human faces. In addtion, by extracting the VGG16 and Xception bottleneck features, I also leveraged transfer learning to speed up my training process without sacrificing accuracy (84% test accuracy).


