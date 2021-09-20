# Classification-with-Transfer-Learning-in-Keras

We will use the MobileNet model architecture along with its weights trained on the popular ImageNet dataset. By using a model with pre-trained weights, and then training just the last layers on a new dataset, we can drastically reduce the training time required to fit the model to the new data . The pre-trained model has already learned to recognize thousands on simple and complex image features, and we are using its output as the input to the last layers that we are training.
Project Structure
The hands on project on Image Classification with Transfer Learning in Keras is divided into following tasks:

# Task 1: Introduction and Importing Libraries
Understanding the problem.

Introduction to the Rhyme interface.

Importing Libraries and Helper functions.

# Task 2: Oxford-IIIT Pet Dataset
Downloading the Pet dataset.

Class and Index Maps.

Extract relevant annotations.

# Task 3: Get Random Batch
Adding functionality to create a random batch of examples and labels.

Image pre-processing with Keras.

Displaying a batch of examples.

# Task 4: Create Model
Downloading the MobileNet v2 architecture and weights.

Creating a new model with MobileNet v2 and a new fully connected top layer.

# Task 5: Model Training
Creating a data generator function.

Calculating training and validation steps

Training the model to fit on the data.

# Task 6: Predictions
Getting predictions on a test batch.

Displaying the test batch along with predictions.
