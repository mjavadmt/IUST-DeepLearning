# Deep Learning Course 
This repository contains assignments of IUST deep learning course. 

## Advance RNN
Goal of this project is to predict label. The dataset consist of value within timeseries and our task is to predict imbalancy of data.
I designed 3 model architecture(Simple RNN, LSTM, GRU) to predict the labels. Also to get better resutls, Data augmentation was also applied. methods like upsampling was implemented to handle imbalancy of data.

## Car Classifier
This repository solves classifying car image into thier producer company. I implemented Custom CNN model to extract image locality, this process has repeated on 2 other layers consecutively, at the end I put a fully connected layer with softmax activation.
methods like earlyStopping and reducing learning rate were also applied to not encounter overfitting. Also I imeplemented other model architecture with pretrained model MobileNetV2 to compare accuracy between creating CNN from scratch and using pretrained weights.

## CIFAR CLASSIFIER 
The main focus of this assignment was to use gird search to see which hyperparameter tunes the best. The tool used for this was **keras tuner**. I search over different number of hidden neurons, dropout and learning rate to fine the most suitable hyperparameters. At the end I evaluated the model and plotted confusion matrix.

## Compare Models Image Classification
I implemented many models such as simple MLP, CNN models to classify cifar dataset.

## Compare Hyperparameters
Comparing the result of *one output neuron with sigmoid classification* and *two output neuron with softmax classification*

## Compare Optimizers
Classifying mnist dataset with comparison of different optimizers such as **AdaGrad, RMSProp and Adam**

## DataAug
See the effect of data augmentation on images. Firstly, I just classified data based on the pure dataset and then added some augmentation technics to see wheter results get better or not. Augmentation methods were *horizontal shift, vertical shift, brigthness, zoom, flip and etc.*

## Image Datasets MLP Classifier
Learning different way of training models with different dataset. analyzing archtiecture of model and implementing some MLP architecture and comparing them.

## MLP OverFit
This assignment challenged to overcome to effect of overfitting. Technics uses for dominating overfitting were *KFold Cross Validation, Weight Regularization(L2) , DropOut and EarlyStopping*