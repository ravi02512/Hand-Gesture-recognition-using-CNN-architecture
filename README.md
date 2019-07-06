# Hand-Gesture-recognition-using-CNN-architecture

## Description:

Built Image classifier using CNN architecture which is able to recognize the hand 10 hand signs with 89 percent accuracy.
The network architecture is given below

Implements a three-layer ConvNet in Tensorflow:
    
    CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> FULLYCONNECTED
    
 Here we used 2 layer conv2d net which is able to detect the important features of from the images and reduces the parameters as well which increases the computatio speed of the network surprisingly.Here we used relu activation function in middle of the network and for output layer i used softmax function.
 
 ## Language of Imaplementaion 
 
 Language :- python3
 Deeplearning Framework :- Tensorflow
 Architecture used:- Convolutional Neural Network
 
 
 ## About the Dataset:-
 
 The format of the dataset is HDF5 which is used for storing the mathematical values.These data set contains the image array train_sign.h5 is trainig dataset which contains 1080 image array and test_sings.h5 contains 120 image array.
 
 ## Dependencies Used 
 ### Math 
 For Basic Mathematical computation
 
 ### Numpy 
 For algebric mathematical computation
 
 ### Matplotlib
 
 For visualizing the dataset and results
 
 ### Tensorflow
 
 For creating the deep neural network and optimizing algorithms
 
 
 
 ## List of Procedures:
 
 First build the network architecture.
 
 Initialize Parameters
 
 Forward Propagation.
 
 Computer cost.
 
 Backpropagation ( or using other optimizing algorithms like Adam and RMS prop)
 
 
 Optiimization algorithms used:- Adam Optization
 
 
 Results:-Trained model for 300 epoch and successfully achieved 89 percent accuracy.
 
 
