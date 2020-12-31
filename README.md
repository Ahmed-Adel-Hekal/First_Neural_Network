# First_Neural_Network

This is my first implementation for my neural network only using NumPy.<br />

# Code Overview 

Code contains important parts like :. <b>

1. Hyperparameter like 
   - iterations : How many times your code will work 
   - learning_rate  : How much experience your network will learn from the previous experience
   - hidden_nodes   : Number of nodes that you will not interact with it   
   - output_nodes   : It depends on your output type 

2. ForwardPropagation : <br>
   Refers to the calculation and storage of intermediate variables (including outputs) for a neural network in order from the input layer to the output layer.
   
3. BackPropagation : <br>
   Refers to the method of calculating the gradient of neural network parameters. <br>
   In short, the method traverses the network in reverse order, from the output to the input layer, according to the chain rule from calculus. <br>
   The algorithm stores any intermediate variables (partial derivatives) required while calculating the gradient with respect to some parameters. <br>
   In shorthand, this is how your network learn (Learning process ).
4. Activation Function :<br>
   the activation function of a node defines the output of that node given an input or set of inputs. (How your output will looks like)
   
 -------------------------------------------------------------------------
# Built With

1- [Numpy](https://numpy.org/) - The fundamental package for scientific computing with Python<br />

# Authors

Origanally this is a part of Deep_Learning_Nanodegree [Udacity](https://www.udacity.com/course/deep-learning-nanodegree--nd101)

***Ahmed_Hekal***
