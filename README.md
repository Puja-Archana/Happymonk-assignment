# Happymonk-assignment
Name: Puja Archana Sahu

mail: puja.archana21@gmail.com

**Problem Statement**:
The problem includes various banknotes which needs to classified as authetic or not. The data set was taken from UCI repository.

**Model Architecture**
The neural network architecture that has been designed for this problem includes 3 layers i.e  one input layer, one hidden layer and one output layer. The input layer contains 8 neurons, the hidden layer contains 32 neurons and the output layer contains one neuron, which predicts the bank note is authenticated or not. This is designed using Keras. The model summary is depicted below. this includes the no of parameters(weights and biases) and the hyperparameters(no. of hidden layers, no of neurons in each layers etc).
![Relu function](https://github.com/Puja-Archana/Happymonk-assignment/blob/main/model_summary.PNG)


I have used relu activation function for the first two layers and sigmoid activation function for the output layer as this problem was a binary classification task.

**Sigmoid or Logistic Activation Function**
![Sigmoid function](https://github.com/Puja-Archana/Happymonk-assignment/blob/main/1.PNG)
- The Sigmoid Function curve looks like a S-shape.
- The main reason why we use sigmoid function is because it exists between (0 to 1). Therefore, it is especially used for models where we have to predict the probability as an output. Since probability of anything exists only between the range of 0 and 1, sigmoid is the right choice.
- The function is differentiable. That means, we can find the slope of the sigmoid curve at any two points.
- The function is monotonic but function’s derivative is not.
- The logistic sigmoid function can cause a neural network to get stuck at the training time.
- The softmax function is a more generalized logistic activation function which is used for multiclass classification.


**Relu**
![Relu function](https://github.com/Puja-Archana/Happymonk-assignment/blob/main/2.PNG)
- The ReLU is the most used activation function in the world right now.Since, it is used in almost all the convolutional neural networks or deep learning.
- As you can see, the ReLU is half rectified (from bottom). f(z) is zero when z is less than zero and f(z) is equal to z when z is above or equal to zero.
- Range: [ 0 to infinity)
- The function and its derivative both are monotonic.
- But the issue is that all the negative values become zero immediately which decreases the ability of the model to fit or train from the data properly. That means any negative input given to the ReLU activation function turns the value into zero immediately in the graph, which in turns affects the resulting graph by not mapping the negative values appropriately.

**Result**
- F1 score was found to be 1.
- ![Relu function](https://github.com/Puja-Archana/Happymonk-assignment/blob/main/4.PNG)
- A heat map of the confusion matrix was made to sjow the reults.
