# Problem Statement:
Fashion MNIST is a dataset of Zalando's article images, consisting of 60,000 training
examples and 10,000 test examples. Each example is a 28x28 grayscale image,
associated with a label from 10 classes. The task is to classify these images into an
apparel category amongst 10 categories on which the dataset is benchmarked.
## Steps Involved:
### Data Preparation and Visualization:
● Loaded the Fashion MNIST dataset.

● Visualized different samples from the dataset.

● Normalized the pixel values of the images to be between 0 and 1 for better

### Model performance.
● Converted the output labels to categorical format for classification.

### Model Building and Training:

Constructed a Neural Network using TensorFlow and Keras.

● The model consist of multiple dense layers with a significant number of
neurons.

● Utilized ReLU activation for hidden layers and softmax activation for the output
layer.

● Trained the model on the prepared dataset.

● Implement callbacks, particularly TensorBoard, to visualize the training process.

## Model Evaluation and Analysis:

● Evaluated the model's performance using a validation set.

● Analyzed the training process with the help of TensorBoard.

● Saved the trained model, including its architecture and learned weights.
