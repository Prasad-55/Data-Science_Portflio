# Problem Statement:
Fashion MNIST is a dataset of Zalando's article images, consisting of 60,000 training
examples and 10,000 test examples. Each example is a 28x28 grayscale image,
associated with a label from 10 classes. The task is to classify these images into an
apparel category amongst 10 categories on which the dataset is benchmarked.
## Objectives:
### Data Preparation and Visualization:
● Load the Fashion MNIST dataset.

● Visualize different samples from the dataset.

● Normalize the pixel values of the images to be between 0 and 1 for better
### model performance.
● Convert the output labels to categorical format for classification.

### Model Building and Training:

Construct a Neural Network using TensorFlow and Keras.
● The model should consist of multiple dense layers with a significant number of
neurons.
● Utilize ReLU activation for hidden layers and softmax activation for the output
layer.
● Train the model on the prepared dataset.
● Implement callbacks, particularly TensorBoard, to visualize the training process.

## Model Evaluation and Analysis:
● Evaluate the model's performance using a validation set.

● Analyze the training process with the help of TensorBoard.

● Save the trained model, including its architecture and learned weights.
