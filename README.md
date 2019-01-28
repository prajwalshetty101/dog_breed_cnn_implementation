# dog_breed_cnn_implementation
CNN project to recognize dog breeds

## Project Overview

In this project for the Udacity Machine Learning Nanodegree, I implemented a CNN with AWS GPU to classify dog breeds or the most resembling dog breed among 133 available breeds when given as input an image of either a dog or a human. I used two pre-trained models `ResNet-50` to detect dogs and `OpenCV-Harr Cascades` to detect human faces. In addtion, by extracting the VGG16 and Xception bottleneck features, I also leveraged transfer learning to speed up my training process without sacrificing accuracy (84% test accuracy).

## Installation

Simply download the juputer notebook and the image directory to get started.

## Usage

Playing around with the dog breed classification hus in ML concepts.
You can add your own images to run the algorithm.


MIT License

Copyright (c) [2019] [Prajwal Shetty]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
