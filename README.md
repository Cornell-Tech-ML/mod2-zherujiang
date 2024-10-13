[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/


## Training Log
### Simple Dataset

#### Model Parameters
* Number of points: 150
* Size of hidden layer: 2
* Learning rate: 0.05
* Number of epochs: 500

#### Training Result
* Time per epoch: 0.089s
* Correct: 150/150
* Loss: 32.5625

<img src="/assets/images/simple.png" width="50%">
<img src="/assets/images/simple_loss.png" width="50%">


### Diag Dataset
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 3
* Learning rate: 0.1
* Number of epochs: 500

#### Training Result
* Time per epoch: 0.133s
* Correct: 148/150
* Loss: 11.7703

<img src="/assets/images/diag.png" width="50%">
<img src="/assets/images/diag_loss.png" width="50%">


### Split Dataset
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 5
* Learning rate: 0.1
* Number of epochs: 500

#### Training Result
* Time per epoch: 0.251s
* Correct: 118/150
* Loss: 59.66

<img src="/assets/images/split.png" width="50%">
<img src="/assets/images/split_loss.png" width="50%">


### XoR Dataset
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 5
* Learning rate: 0.5
* Number of epochs: 500

#### Training Result
* Time per epoch: 0.266s
* Correct: 143/150
* Loss: 17.8042

<img src="/assets/images/xor.png" width="50%">
<img src="/assets/images/xor_loss.png" width="50%">


### Circle Dataset
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 5
* Learning rate: 0.5
* Number of epochs: 500

#### Training Result
* Time per epoch:
* Correct: 
* Loss: 

<img src="/assets/images/circle.png" width="50%">
<img src="/assets/images/circle_loss.png" width="50%">


### Spiral Dataset
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 16
* Learning rate: 0.1
* Number of epochs: 450

#### Training Result
* Time per epoch: 1.735s
* Correct: 88/150
* Loss: 100.1771

After I tried differnt hyperparameters, I found that the model is not able to fit the data well. The loss is not decreasing over time so I stopped the training before it reaches 500 epochs.

<img src="/assets/images/spiral.png" width="50%">
<img src="/assets/images/spiral_loss.png" width="50%">