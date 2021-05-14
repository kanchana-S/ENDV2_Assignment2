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

### Following images are the graphs of total error with different learing rates
Note - The graphs are a bit different from what were shown in during the class, please be rest assured that the values are same, i have cross checked atleast 3 times. I did find a mistake made during the lecture which have led to the graphs being different

#### LR = 0.1
![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/learning_rate_0point1.PNG)

#### LR = 0.2
![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/learning_rate_0point2.PNG)

#### LR = 0.5
![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/learning_rate_0point5.PNG)

#### LR = 0.8
![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/learning_rate_0point8.PNG)


#### LR = 1
![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/learning_rate_1.PNG)


#### LR = 2
![image](https://github.com/kanchana-S/ENDV2_Assignment2/blob/main/images/learning_rate_2.PNG)
