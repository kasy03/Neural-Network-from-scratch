# Neural-Network-from-scratch
Implementation of fully connected neural network with a static architecture. 

- Input layer
- Dense hidden layer with 512 neurons, using relu as the activation function
- Dropout with a value of 0.2
- Dense hidden layer with 512 neurons, using relu as the activation function
- Dropout with a value of 0.2
- Output layer, using softmax as the activation function


The model uses categorical crossentropy as its loss function. 
Optimized the gradient descent using RMSProp, with a learning rate of 0.001 and a rho value of 0.9.
The evaluation of the model is using accuracy.
This was in an attempt to reproduce from scratch [example from the Keras documentation](https://keras.io/examples/mnist_mlp/).
