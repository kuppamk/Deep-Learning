# Deep learning Using Tensorflow & Keras

This project has two parts which deals with familirization of tensorflow for Deep Learning & Solving MNIST dataset using deep leanring with less no of parameters.

## Tensorflow Familarization for Deep Learning

It is typical flow of training deep leanring model with debug facilites using tensorflow graphs. Basic unit in tensorflow is Tensor and all computations are represented as graphs. Here are the steps
1. define image, label varibles
2. create a function to store summaries of all parameters for debugging.
3. create a various layer functions includes summary function.
4. define simple model using the layers created in previous step
5. define loss, optimizer, and accuracy
6. create a session, initialize all the variables, summary files for train & test
7. train the model for some epochs mean while you can open tensorboard to view the training using summaries.


# MNIST Deep learning Model

    Generally Deep Learning models are heavy interms of no of parameters so I thought of developing model with less parameters and not loosing accuracy. Hence I acheived model with less than 18K parameters  and got accuracy as 99.66. The idea is reduce the no of parameters is acheived using seperable convolution and removing dense layer.
