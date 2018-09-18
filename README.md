# CancerNN
This repo contains the implementation of simple neural network that uses the data of tumour included in a csv and classify the problems into Malignant or Benin.

## Code Overview
Start by importing all the relevent libraries which are required in here. Keras on top of TensorFlow was used for this purpose.

A function into_num(classify) is defined to change the catagories into labels from Malignant(M)/Benin(B) to 1/0 values that are understood by nerual networks.

Load required CSV and do the preprocessings which include checking for the null values,making sure all the inputs(X)/outputs(Y) are numerics, separation of inputs and outputs, spliting of traing and testing data, normalising the inputs etc.  

Initialise and compile the neural network with four dense layers all layers ,except for the last one, followed by the droput layer. 
