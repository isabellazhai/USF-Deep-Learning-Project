# USF-Deep-Learning-Project

# Authors: Wei He, Isabella Zhai
## The goal of this porject is to conduct an exploration of some basic deep learning techniques for object detection and classification tasks. Specifically, we would love to apply deep learning to do image classification for animal pictures. The intention of this page this to provide a general overview of this project, the steps we took, as well as the modeling outcome.

# Outline
1. Introduction<br />
  1.1 Goal and Overview<br />
  1.2 Dataset<br />
2. Modeling<br />
  2.1 Data Augmentation<br />
  2.2 CNN<br />
3. Conclusion and Results<br />

# Introduction
### Goal
The goal of this project is to explore the basics of image detections and apply deep learning techniques to classify animal images into different categories. Why we do this? Because animals (especially cats) are cute! Before the modeling, we included a step of data augmentations on the original animal dataset in order to increase the amount of data by adding slightly modified copies of already existing data or newly created synthetic data from existing data. It acts as a regularizer and helps reduce overfitting when training a machine learning model. We then applied a CNN model on our image dataset using Tensorflow. We picked Tensorflow instead of Pytorch because both of the team member felt that the former one had easier UI to work with. <br />

### Dataset


![Model_performance](model_performance_1.jpg)

