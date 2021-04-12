# Introduction to Neural Networks
## **AND, OR, XOR** using neural networks

1. AND
![](images/26-21.png)

2. OR
![](images/27-54.png)

3. XOR
![](images/28-41.png)
![](images/30-35.png)

## Intuition: find the binary classification line.

Points correctly classified are good. Points are misclassified want the line to move closer to them. 

To move a line closer to a point, we just need to modify the line equation's coefficient by subtracting the points coordinates (with bias 1) (TODO: math?). We need to use a learning rate to control the speed of the line moving to the point.

![](images/42-46.png)

Algorithm:

![](images/34-34.png)

We need a continuous and differentiable error function in order to use gradient decent.

![](images/41-29.png)

We use activation function to let each unit returns continuous probabilities:

![](images/03-10.png)

### Softmax
Essentially, we want to convert the generated scores (z) to probability range in [0, 1]. Since the z could be negative, we need to apply exponential before normalization.

![](images/13-50.png)

### One-hot Encoding
If we have multiple classes, we can not simply label then as 1, 2. 3, ... Because that will introduce dependencies, e.g, 1 is closer to 2 than 5. We can use one-hot encoding to generate independent labels.
![](images/30-16.png)

## Maximum Likelihood
A good model should give higher probabilities to sampling events occurred. 

![](images/33-41.png)

# Cross Entropy
Given a bunch of events and probabilities, cross entropy measures how likely the events happen based on the probabilities. If it is very likely, then we have a small cross entropy. Otherwise, we have a large cross entropy.

A good model has small cross entropy to sampling events.

![](images/38-24.png)
![](images/48-13.png)

## Logistic Regression (Binary Classification)
![](images/56-18.png)

![](images/10-56.png)

# Training Neutral Networks
Keep training the neutral network until testing error start increasing. 

![](images/35-16.png)

## Regularization
![](images/38-43.png)
![](images/39-05.png)
![](images/39-24.png)
![](images/40-29.png)
![](images/41-47.png)

![](images/43-27.png)
![](images/44-24.png)

## Vanishing Gradient
![](images/45-14.png)
![](images/45-52.png)
![](images/46-09.png)

Batch vs Stochastic Gradient Descent

![](images/49-23.png)
![](images/50-43.png)

# Recurrent Neutral Networks
![](images/09-01.png)
![](images/15-22.png)
![](images/12-39.png)
![](images/20-07.png)
![](images/21-17.png)
![](images/22-30.png)
![](images/31-07.png)
![](images/23-21.png)
![](images/23-51.png)