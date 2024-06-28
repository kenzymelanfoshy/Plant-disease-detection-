# Plant Village Disease Classification
This project focuses on classifying plant diseases using a Convolutional Neural Network (CNN) with TensorFlow and Keras.

# Project Description
The Plant Village Disease Classification project aims to accurately identify and classify diseases in potato plants using image recognition techniques. This is achieved by training a CNN model on a dataset of plant images, which includes healthy plants and plants affected by early blight and late blight.

# Installation Instructions
To set up the project, follow these steps:

- Clone the repository:

git clone https://github.com/your-username/plant-village-disease-classification.git
cd plant-village-disease-classification

- Install the required libraries:

pip install numpy pandas tensorflow matplotlib keras

Download the dataset and place it in the appropriate directory.

# Usage Instructions
Prepare the dataset: Copy the relevant folders from the source directory to the destination directory.


# 1. Import Libraries
First, the project imports the necessary libraries:

NumPy: For numerical operations.
Pandas: For data manipulation.
TensorFlow: For building and training the machine learning model.
Matplotlib: For data visualization.
Keras: A high-level API for TensorFlow to simplify model building.

# 2. Set Up Directories
The project defines the source and destination directories for the dataset. The source directory contains the original dataset, while the destination directory is where specific folders (containing images of healthy and diseased plants) will be copied.


It then creates the destination directory (if it doesn't already exist) and copies the necessary folders from the source to the destination.

# 3. Initialize Constants
Constants are initialized to define the parameters for image processing and model training:

IMAGE_SIZE: The size to which each image will be resized.
BATCH_SIZE: The number of images to process in a batch.
CHANNELS: The number of color channels in the images.
EPOCHS: The number of times the entire dataset will be passed through the model during training.

# 4. Create Image Dataset
The project uses TensorFlow to create an image dataset from the specified directory. The images are shuffled and batched according to the previously defined constants.

# 5. Display Class Names
The class names of the dataset (i.e., the categories of plant conditions) are printed to the console.

# 6. Data Visualization
To get an idea of what the data looks like, the project visualizes some sample images from the dataset. This helps in understanding the variation in the images and the conditions being classified.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Contact Information
For any questions or inquiries, please contact kenzy.abdlatif@ejust.edu.eg .
