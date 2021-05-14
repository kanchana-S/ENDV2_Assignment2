# ENDV2_Assignment2

## Step by Step Explanation of Backpropagaton

### This is our neural network with a single hidden layer

![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/neural%20network.PNG)

### First step is to write down all our basic formulas of calculating node values, activated and other wise for the hidden layer and the output layer. Found using the following formulae 
(Sig represents sigmoid function)

![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/formulae_1.PNG)


### The next step is to find partial derivative of E_total w.r.t. to the various weights starting with the most recent and working our way to the back. These when calculated can be seen in the following image

![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/all_derivatives.PNG)

### Following this, the weights can now be updated for the next iterations using the following formula
W_new = W_old - LR*dE/dW_old
