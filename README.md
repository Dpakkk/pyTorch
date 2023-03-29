# pyTorch
First part is to get familiar with pyTorch and get familiar with tensors, it's operations, exploring different sizes of tensors, etc. In the second part the processes involve are of these topics:
- Create a pytorch class for a neural network with 3 inputs, one hidden layer with 5 neurons and ReLU activatioin function, one output layer with 2 outputs
- Instantiate the class to create a model. Access the weights and biases and print them
- Create a tensor X with 2 samples and 3 features randomly from a uniform distribution. Suppose the labels are 0 and 1, respectively for these two samples
- Define crossentropy
- Define an optimizer with stochastic gradient descent. Set the learning rate to 0.1
- Set the gradients of the model to zero. Do backpropagation and find the jacobians of loss with respect to weights and biases in the first and second layers
- Update the parameters
