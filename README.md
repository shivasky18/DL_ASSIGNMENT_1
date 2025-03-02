# DL_ASSIGNMENT_1

# MNIST Classification using Neural Networks

This project implements a neural network model using Keras for classifying images in the MNIST dataset. The model can be customized with different hyperparameters such as the number of layers, neurons per layer, and the optimizer.

## Requirements

To run the code, you will need to install the following Python libraries:
- TensorFlow (includes Keras)
- NumPy
- Pandas

You can install the necessary dependencies using `pip`:

```bash
pip install tensorflow numpy pandas

Dataset
The MNIST dataset consists of 28x28 grayscale images of handwritten digits from 0 to 9. The dataset is divided into:

60,000 training images
10,000 test images
File Structure
mnist_classifier.py: Main Python script for building, training, and evaluating the model.
README.md: This file containing instructions.

How to Train the Model
Clone or download this repository.
Run the script mnist_classifier.py:
python mnist_classifier.py

This will automatically:

Load the MNIST dataset.
Split the data into training, validation, and test sets.
Build a neural network model.
Train the model on the training data for 10 epochs.
Evaluate the model on the test data and print the test accuracy and loss.

Customizing the Model
You can modify the following hyperparameters in the main() function:

Number of Hidden Layers: num_layers
Neurons per Layer: neurons
Optimizer: optimizer (e.g., Adam, SGD, RMSprop)
Activation Function: activation (e.g., relu, sigmoid)
Batch Size: batch_size
Epochs: epochs
For example, to change the number of hidden layers to 3, set the num_layers variable in the main() function to 3.

Example Output
After training, the script will output the test accuracy and loss, similar to:

yaml
Copy

Epoch 1/10
1875/1875 [==============================] - 5s 2ms/step - loss: 0.2967 - accuracy: 0.9157 - val_loss: 0.1487 - val_accuracy: 0.9571
...
Test accuracy: 98.30%
Test loss: 0.0452
