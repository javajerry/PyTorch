# PyTorch

## Machine Learning vs. Classical Programming
The approach we've taken in this tutorial is very different from programming as you might know it. Usually, we write programs that take some inputs, perform some operations, and return a result.

However, in this notebook, we've defined a "model" that assumes a specific relationship between the inputs and the outputs, expressed using some unknown parameters (weights & biases). We then show the model some know inputs and outputs and train the model to come up with good values for the unknown parameters. Once trained, the model can be used to compute the outputs for new inputs.

This paradigm of programming is known as machine learning, where we use data to figure out the relationship between inputs and outputs. Deep learning is a branch of machine learning that uses matrix operations, non-linear activation functions and gradient descent to build and train models. Andrej Karpathy, the director of AI at Tesla Motors, has written a great blog post on this topics, titled Software 2.0.

This picture from book Deep Learning with Python by Francois Chollet captures the difference between classical programming and machine learning:

![plot](./oJEQe7k.png)


