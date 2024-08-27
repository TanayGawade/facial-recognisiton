# facila-recognisiton

CNN Introduction: Building a Simple Face Recognition Model Using Keras
Objective:
This guide walks you through the process of creating a basic Convolutional Neural Network (CNN) for face recognition using Keras. The steps include setting up the environment, processing the dataset, building the model, and evaluating its performance.

Step-by-Step Instructions:
Step 1: Import Required Libraries

Begin by importing the necessary Python libraries. This includes Keras, NumPy, Matplotlib, and any other dependencies required for building and training the CNN model.

Step 2: Dataset Loading and Normalization

Load your dataset and normalize the images. Typically, images are in the form of a Uint8 matrix, which needs to be converted to a float or double format for precise calculations.

Step 3: Splitting the Dataset

Divide the dataset into training and validation subsets to prevent overfitting. Typically, 30% of the dataset is used for validation, but due to the limited number of images in this dataset, we will use only 5% for validation.

Note: Monitoring validation accuracy is crucial. If training accuracy increases while validation accuracy remains the same or decreases, it indicates overfitting, and you should stop training.

Step 4: Resizing Images

For the CNN to process the images correctly, all images must be resized to the same dimensions.

Step 5: Constructing the CNN Model

The CNN architecture is built using three main types of layers:

Convolutional Layer
Pooling Layer
Fully Connected Layer
You can experiment with different architectures by adjusting the number and position of these layers.

Step 6: Training the Model

Train the model using the training dataset while validating against the validation set. Monitor the accuracy and loss to fine-tune the model.

Step 7: Plotting the Results

Finally, plot the training and validation accuracy and loss to visualize the model’s performance.

Dataset link = https://drive.google.com/drive/folders/1sPnuJkRjJ7RMQJsrfh3oIVymUhEOWXIQ?usp=sharing
