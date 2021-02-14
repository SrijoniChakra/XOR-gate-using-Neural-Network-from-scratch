# XOR-gate-using-Neural-Network-from-scratch
This code implements neural network from scratch. I have performed forward propagation and back propagation to compute the gradient on a neural network with 2 layers. The neural network has 2 input units (d(0) = 2), 3 hidden units (d(1) = 3), 1 output unit (d(2) = 1). 
Dimensions of the neural net are as follows:
1) Input layer dimensions: (4,2)
2) Layer1 weights: (2,3)
3) Layer2 weights: (3,1)
4) Output layer: (4,1)
I have used tanh as the activation function on the neurons. For gradient, squared error has been used as the error measure.If the output of the neural net is close to 1 then its considered as 1 while output close to 0 or negative is considered as 0.
