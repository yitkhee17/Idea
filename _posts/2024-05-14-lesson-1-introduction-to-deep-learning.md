---
title: "Lesson 1: Introduction to Deep Learning"
date: "2024-05-14"
excerpt_separator: "<!--more-->"
categories:
  - Lesson
tags:
  - Basic
  - Lesson
  - Deeplearning&Neuralnetwork
---

# Neural Network
Neural network is made up of stacks of neuron units. 

1. Single neuron illustration
![image](https://github.com/yitkhee17/Idea/assets/135970016/11056fe2-8d1b-4b0d-99a3-6ed1c099d61d)

2. Stacked neuron illustration
![image](https://github.com/yitkhee17/Idea/assets/135970016/b0bcad58-b3ed-4cb7-9247-9b70c105c7a4)

## Explaining with House Price Prediction
1. Single neuron application: The size of house affecting the price of the house.
![image](https://github.com/yitkhee17/Idea/assets/135970016/7f866737-d7d5-4fa3-aefe-5375a6a17905)

2. Stacked neuron application: Many features affecting the price of the house.
![image](https://github.com/yitkhee17/Idea/assets/135970016/153cf204-55eb-4daf-9d55-ca6095813b6a)


# Supervised Learning with Neural Networks

## Supervised learning
A type of machine learning, clearly identified x and y to solve the problem.
|Input (x)|Output (y)|Application|Neural Network|
|---|---|---|---|
|Home features|Price|Real Estate|Standard NN|
|Ad, user info| Click on ad? (0,1)|Online Advertising|Standard NN|
|Image|Object(1,...,1000)|Photo tagging|Convolutional NN|
|English|Malay|Machine Translation|Recurrent NN|
|Image, Radar info|Position of other cars|Autonomous Driving|Customized/Hybrid NN|

![image](https://github.com/yitkhee17/Idea/assets/135970016/e0e712d9-1675-433a-801f-db41134c7708)

### Data
1. Structured data: 
All information needed is ready in a table, with the labelled of prediction
2. Unstructured data:
Audio ,image: feature = pixels, text: feature = individual word

# Advancement of Deep Learning
As we evolved into the era of digital, more data are available in digtal form, and the performance of the deep learning highly-dependent on the training data. 

![image](https://github.com/yitkhee17/Idea/assets/135970016/d55c50f5-211c-4352-8675-174db01fd2d1)

With a smaller training set, performance from these models does not show high difference. In fact, the performance would highly depend on the feature engineering process. As the size of training data increase, a huge difference in the model performances are observed (Large NN performs the best).

> Higher performance:
> 1. Train **BIG neural network** to take advantage from
> 2. **HUGE amount of data**.
> Sadly, improving these two metrics contributes to a threshold where the model is oo big to train or the data ran out.

## Scale drives deep learning process
1. Size of neural network
2. Size of data
3. Computation resource [CPU, GPU]
4. Algorithms
  - activation function: [sigmoid -> ReLU] for increase the learning rate and gradient descent.
  - ![image](https://github.com/yitkhee17/Idea/assets/135970016/0cac5a13-4421-46ee-808e-40c148b045fc)

The improvement of computational resources and algorithms aim to speed up the training process. Following the recursive ideation process, the longer the experiment time (training time), the longer the time to conduct a full process.   
![image](https://github.com/yitkhee17/Idea/assets/135970016/6f3672a3-1ed2-4884-9038-7d76f9884677)
