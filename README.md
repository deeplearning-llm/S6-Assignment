# Creating a Simple Neural Network Using Excel Sheet 
<img width="959" alt="NN" src="https://github.com/deeplearning-llm/S6-Assignment/assets/135349271/4e41de01-3072-49dd-b706-098865464bb1">

The Excel sheet helps us to create a simple Neural Network The Neural Network Architecture comprises of the Following :

- Input Layers - We have considered only two fetaures as input [i1,12]
- Hidden Layers - hidden layers comprises of two operation i,e( dot product between input vector and its weights(h1,h2) , Introducing Non-Linearity using a sigmoid         activation(a_h1,a_h2))
- Output Layers - two neurons in the final layers which takes in inputs from the previous layers and produces two outputs using the operation mentined above i.e(o_1, o_2, a_o1 , a_02) Weights are Initialized Randomly From the Output Layers we calculate the Losses Et1 =(t1-a_o1) and Et2= (t2-a_o2). The total loss Etotal = Et1+Et2 We try to minimize  this loss with the help of backward propagation where we try to adjust the weights to minimize the losses . Various Learning rates are used to understand the behaviour of convergence of the loss function to a minima
- We see that with increase in learning rate from [0.1, 0.2, 0.5, 0.8, 1.0, 2.0] , The loss function converging with fewer number of epochs


