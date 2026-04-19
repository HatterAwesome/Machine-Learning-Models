# Machine-Learning-Models 
  1. Added a file called House Visualization Model. Finds averages of household income, bedrooms, and the house proximity.

# Findings from Titanic Dataset
  1. This project applies supervised machine learning to the Titanic dataset to predict passenger survival. The data was explored using summary statistics and visualizations, and missing values were cleaned as part of the preprocessing step. A Logistic Regression model was trained using an 80/20 train-test split, achieving an accuracy of 81%. The results demonstrate how classification models can be used to analyze historical data and make survival predictions based on passenger characteristics.

# Building CNN Dataset 
  1. Created a CNN dataset that collected, processed, and augmented data which used framworks like TensorFlow.

# ResNet cifar10 
  1. ResNet is a highly effective convolutional neural network architecture for the CIFAR-10 image classification dataset, widely recognized for solving the vanishing gradient problem in deep learning via skip connections

# K-Means 
  1. Implements the K-Means clustering algorithm from scratch using Python and NumPy. A synthetic dataset is generated using make_blobs, and the algorithm assigns points to the nearest centroid, updates centroids iteratively, predicts cluster labels, and visualizes the final clusters and centroids. This notebook demonstrates unsupervised learning step-by-step.

# SVM
  1. Demonstrates a Support Vector Machine classifier using the Iris dataset. The notebook includes train-test splitting, model training, prediction, and evaluation with accuracy, confusion matrix, and classification report. Optional 2D visualization of predicted labels is included for easy interpretation. This notebook is designed for step-by-step understanding of supervised learning with SVMs.
# StreetHouseDataset
Using TensorFlow, I modified the original tutorial to use the Street View House Numbers (SVHN) dataset instead of MNIST. The key change involved replacing 28×28 grayscale images with 32×32 RGB images, requiring updates to both the generator and discriminator architectures to handle three color channels and larger image dimensions. The generator was adjusted to output 32×32×3 images, while the discriminator was modified to accept this new input shape. To improve training speed in Google Colab, the dataset was reduced to 10,000 images, the number of epochs was lowered to 5, and the batch size was set to 64. During training, generated images were saved after each epoch and displayed in a 4×4 grid format. The results show that the model begins to learn structural patterns from the dataset, but the generated images remain blurry and not fully recognizable due to limited training time and reduced dataset size. Overall, this project demonstrates how GANs can be adapted to real-world datasets and highlights the importance of sufficient data and training duration for producing high-quality generated images.
