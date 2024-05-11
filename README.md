In TensorflowClassificationPracticals1.ipynb, the following tasks were performed:

1. Make_Circles Binary classification example with Tensorflow
   
  Build Keras sequential layers using the relu activation function on the top layers to achieve non-linearity
  Use the sigmoid function on the output layer for binary classification
  Use binary_crossentropy as a loss function for binary classification
  Buid sequential layers, compile with optimizer (Adam or SGD) choosing the right (sensitive) learning rate and fit for some number of epochs.

2. Multi-class classification with the inbuilt Fashion MNIST dataset
   
  Build sequential layer, using relu activation function in the inner layers and specifying input shape at the top layer
  Use softmax activation function at the output layer specifying the number of classes
  Use SparseCategoricalCrossentropy as the loss function for multi-class classification.

In the CNN with Tensorflow file, convolutional neural network in Tensorflow was used on the Food101-dataset for classification.
First, two classes of food (Pizza and steak) were classified using CNN binary classification using a model that resembles the TinyVGG. 
Another instance was demonstrated with data augmentation.
Secondly, mutli-class classification was performed with 10 classes of food.
Also, data augmentation was performed on the multi-class classification even though the performance did not incur a high accuracy.
