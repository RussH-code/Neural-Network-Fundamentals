# Neural-Network-Fundamentals (modify)

---

## Breif Introduction of a Neural Network
Neural networks are core in deep learning. It consists of layers of interconnected nodes that resemble neurons in human brain. In this notebook, we explore a python library `tensorflow` to implement neural networks. 

![](https://github.com/RussH-code/Neural-Network-Fundamentals/blob/main/neural%20network.PNG) 

Photo: https://wiki.pathmind.com/neural-network

All the computation happends in the nodes. Each node has a set of weights and bias. The input from the previous layer is run through the subsequent layer and at each node the following equation is used to compute the output.

output = bias + weights * inputs

After this, the output is put through an activation function that transforms the output. Popular activation function such as ReLu transform input with the `max(0, x)` equation. Essentially, input less than 0 are default to 0 and do not carry any weight. Thus, the node is said to be 'deactivated'. Conversely, positive input will be preserved, and nodes are 'activated'.

![](https://github.com/RussH-code/Neural-Network-Fundamentals/blob/main/relu.PNG) Photo: <a href="https://www.youtube.com/watch?v=68BZ5f7P94E">Neural Networks Pt. 3: ReLU In Action!!!</a>

This notebook focuses more on the coding part of neural network. For more detailed mathematical explanation on how neural networks work under the hood, there are some great resources for you to review.

1. <a href="https://youtu.be/CqOfi41LfDw">StatQuest Neural Network Series</a>
2. <a href="https://youtu.be/aircAruvnKk">3Blue1Brown - What is Neural Network</a>

In this notebook we will 

1. Go through the steps of implementing a basic neural network
2. Use neural network on regression tasks
3. Use neural network on classification
4. Introduce Convoltional Neural Network.

---
References:
1. <a href="https://youtu.be/tpCFfeUEGs8">Learn TensorFlow and Deep Learning fundamentals with Python</a>
2. <a href="https://youtu.be/5tvmMX8r_OM">MIT Introduction to Deep Learning</a>
