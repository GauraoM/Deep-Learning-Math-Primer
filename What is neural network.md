Activation function has a value between 0 - 1. So when neuron has some value like 0.60 it is activated.
Neural network has 1 input layer, many activation layers and single output layer. Activation in one layer determines the activation in another layer. The brightest neuron in the output layer determines the output value. 

Every neuron is connected to another one by some weights. To determine whether the neuron is activated or not is determine by w1a1 + w2a2 + w3a3 + w4a4 +----+wnan like for detecting particular edge. Output should have value larger than one ,so in-order to pushes the value between 0-1 we need to apply some activation function like sigmoid and add some bias which tells us when the neuron is meaningfully activated. In this way each neuron is connected to another neuron with some activation * (weights+bias) for example: 784*16+16*16+16*10.

Learning means find a right biases and weights.