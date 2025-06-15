# Food-Classification

This project implements a convolutional neural network (CNN) to classify food images using the Food-101 dataset.

The architecture for this model includes:
- Convolutional Layers with ReLU activation
- Batch Normalization
- MaxPooling Layers
- Dropout 
- Fully Connected Dense Layers
- Final Dense Layer with Softmax dor multi-class classification

The project uses the following libraries:
- TensorFlow and Keras: For building and training the CNN model.
- Numpy, Pandas: For data manipulation
- Matplotlib: For visualization
- os, shutil, random: For file handling

Steps to run model
1. Clone the repository or open the notebook
2. Download and extract the Food-101 dataset
3. Instal required packages
4. Run the Jupyter Notebook

Dataset Reference
Food-101 Dataset:
- URL: [Food-101 Dataset](https://data.vision.ee.ethz.ch/cvl/food-101.tar.gz)
- Description: Contains 101 food categories, each with 750 training images and 250 test images, totaling 101.000 images.

Paper Research Reference
- Malina Jiang. *Food Image Classification with Convolutional Neural Networks.* Standford University, Fall 2019.
 - [Paper Link](https://cs230.standford.edu/projects_fall_2019/reports/26233496.pdf)
