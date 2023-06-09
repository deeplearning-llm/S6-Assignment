# Creating a Simple Neural Network Using Excel Sheet 
<img width="959" alt="NN" src="https://github.com/deeplearning-llm/S6-Assignment/assets/135349271/4e41de01-3072-49dd-b706-098865464bb1">

The Excel sheet helps us to create a simple Neural Network The Neural Network Architecture comprises of the Following :

- Input Layers - We have considered only two fetaures as input [i1,12]
- Hidden Layers - hidden layers comprises of two operation i,e( dot product between input vector and its weights(h1,h2) , Introducing Non-Linearity using a sigmoid         activation(a_h1,a_h2))
- Output Layers - two neurons in the final layers which takes in inputs from the previous layers and produces two outputs using the operation mentined above i.e(o_1, o_2, a_o1 , a_02) Weights are Initialized Randomly From the Output Layers we calculate the Losses Et1 =(t1-a_o1) and Et2= (t2-a_o2). The total loss Etotal = Et1+Et2 We try to minimize  this loss with the help of backward propagation where we try to adjust the weights to minimize the losses . Various Learning rates are used to understand the behaviour of convergence of the loss function to a minima
- We see that with increase in learning rate from [0.1, 0.2, 0.5, 0.8, 1.0, 2.0] , The loss function converging with fewer number of epochs




![Loss with Epochs for Learning Rate = 0 1     (1)](https://github.com/deeplearning-llm/S6-Assignment/assets/135349271/eac3f8c1-a92f-46cf-a6c6-277960ac899d)


![Loss with Epochs for Learning Rate = 0 2  ](https://github.com/deeplearning-llm/S6-Assignment/assets/135349271/b4892101-5360-49b9-9570-4de5e19de7da)


![Loss with Epochs for Learning Rate = 0 5  ](https://github.com/deeplearning-llm/S6-Assignment/assets/135349271/2b45fee6-c173-46c7-b5c1-36fc16d13835)


![Loss with Epochs for Learning Rate = 0 8 ](https://github.com/deeplearning-llm/S6-Assignment/assets/135349271/32a56514-b73f-469b-8b6f-8284f10459c6)


![Loss with Epochs for Learning Rate = 1 0](https://github.com/deeplearning-llm/S6-Assignment/assets/135349271/8da15ff2-c39f-459d-a529-0ee0da0dd438)


![Loss with Epochs for Learning Rate = 2 0](https://github.com/deeplearning-llm/S6-Assignment/assets/135349271/1b88d81f-1613-4e7e-bf83-c7e82e4b4643)
