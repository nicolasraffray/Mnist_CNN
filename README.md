# CNN 

The perpose of this project is to get to grips with keras and tensorflow by trying to classify handwritten digits from the mnist dataset. Along with to test my understanding of CNNs. Currently I'm not sure if the CNN architecture is optimal but will look into the most optimal network for the problem when the model is up and running.

## Stage 1 
----
Beginning with two layers 32 kernels in each, with the two sets being of size (2,2) and (3,3) respectively. And having stride length of 1 and 2 respectively. Both layers are followed by maximal pooling layers. 

The loss function used is a categorical cross entropy loss function with an optimizer of rmsprop. 

A summary of the model can be found below

![alt text][./stage1_spec.png]