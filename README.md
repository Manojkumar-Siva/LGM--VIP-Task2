# LGM--VIP-Task2

## Handwritten Digit Classification with CNN and TensorFlow
This project aims to develop a neural network capable of classifying handwritten digits using the MNIST dataset. The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits ranging from 0 to 9.


## Steps of the Project:

### Step1: Data Preprocessing:

Load the MNIST dataset and split it into training and testing sets.

Normalize the image pixel values from 0-255 to 0-1 to enhance model training efficiency.

One-hot encode the labels to convert them into a format suitable for multi-class classification.


### Step2:Build the CNN Model:

Construct a Sequential model with an input layer matching the image dimensions (28, 28, 1).

Add convolutional layers to extract features, followed by pooling layers to reduce dimensionality.

Include dense layers for classification, with the output layer using softmax activation for predicting digit classes.



### Step3:Compile and Train the Model:

Compile the model using the categorical_crossentropy loss function and adam optimizer.

Train the model on the training dataset for a specified number of epochs and validate it using the test dataset.



### Step4:Evaluate the Model:

Use the trained model to predict classes for the test data.

Assess model performance using accuracy metrics, confusion matrix, and classification report to identify prediction accuracy and errors.



### Step5:Predict on New Images:

Load and preprocess external images to match input dimensions.

Use the trained model to make predictions on these images and visualize the results.
