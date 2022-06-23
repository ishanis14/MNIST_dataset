# MNIST_dataset

A very simple beginner level project involving the concepts of Deep Learning and Computer Vision

What did I do in this project ?
I studied on how I can create a neural network which could classify numerical digits from a dataset. 

Tools and Concepts used :
1. Python 
2. Artificial Neural Networks (ANN)

MNIST DATASET: The MNIST dataset is a large database of handwritten digits that is commonly used for training various systems. It contains 70,000 images of handwritten digits. 

Neural Networks are basically algorithms inspired by the brain. So an artificial neural network is made up of 3 layers :
1. Input Layer 
2. Hidden Lyer 
3. Output Layer 

Deep Learning comes into play when it is used to extract useful pieces of information or make decisions using Neural Networks. 

The major steps which have been carried out are: 
1. importing the modules we require
2. loading the dataset 
3. plotting the dataset 
4. creating a neural network model 
5. training the model which we have created 
6. finally testing the model! 
7. analyzing the accuracy and the loss 

With respect to this project and the code I have written, we first start by importing all the useful modules.

What are Modules?
Modules are files which contain functions which can be used according to our requirements. 

Then after importing we can use either Keras or Tensorflow to build our neural network. 
Tensorflow is a free,open source and more detailed library used to develop neural networks, it is a bit tough to code so I have used Keras (which is a more easier to use tool and is built upon TensorFlow) for learning purposes. Apart from developing neural networks, Keras also has the ability to download Datasets like MNIST. 

After downloading the dataset we will divide the data into 2 sets, one will be the training dataset and the other will be the testing dataset. Generally 80% of data is used for training and 20% for testing. 
So here 60,000 images will be used for training and 10,000 for testing.

1. For creating the model, first we will make it sequential which means that one layer will be connected to the next layer. 

2. So the first layer that is the input layer will be a vector because MNIST is not an image processing neural network so it takes data in vector form and not in a matrix form. So first the matrix is flattened into a vector. Each image can be visualised as a matrix of 28 by 28 pixels which needs to be flattened into a 1-D vector of 784 values. 

3. Now Neural Networrks are linear that means that if we multiply the input with the weights and add a bias then we get a linear output. But, real life applications are not linear so to get a non linear output we need to use an activation function which is used in hidden layers to give us a non linear output. There are man activation functions but here I have used softmax. 

4. To figure out the accuracy of our neural network we introduce a loss function which gives us a numerical estimate of how much the neural network has to be corrected   
