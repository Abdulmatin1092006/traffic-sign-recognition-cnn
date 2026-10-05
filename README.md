# Traffic Sign Recognition Using Convolutional Neural Network

A deep learning project for recognizing and classifying traffic signs using a Convolutional Neural Network (CNN).

## 📌 Project Overview

Traffic sign recognition is an important computer vision task used in intelligent transportation systems and driver assistance applications.

In this project, a Convolutional Neural Network is trained to classify images of traffic signs into different categories using the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

## 🎯 Objectives

- Build a CNN-based image classification model.
- Load and preprocess traffic sign images.
- Visualize sample images from different classes.
- Train and validate the CNN model.
- Evaluate the model on unseen test data.
- Analyze performance using accuracy and a confusion matrix.
- Generate predictions for sample traffic sign images.

## 📊 Dataset

The project uses the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset.

The dataset contains images belonging to multiple traffic sign categories and is widely used for traffic sign classification research and computer vision experiments.

The dataset is loaded using the `torchvision` dataset utilities.

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## 🔍 Project Workflow

1. Load the GTSRB dataset
2. Explore and visualize sample traffic sign images
3. Preprocess and normalize the images
4. Split the data into training and validation sets
5. Build a Convolutional Neural Network
6. Train the CNN model
7. Monitor training and validation performance
8. Evaluate the model on the test dataset
9. Generate a confusion matrix
10. Test the model on sample images

## 🧠 CNN Architecture

The project uses a Convolutional Neural Network designed for image classification.

The network learns visual patterns from traffic sign images through convolutional and pooling layers and then uses fully connected layers to classify the images into their respective traffic sign categories.

## 📈 Model Performance

The trained CNN achieved:

**Test Accuracy: 95.19%**

The training and validation accuracy increased consistently during the five training epochs, while the loss decreased substantially.

The confusion matrix also shows that the model correctly classifies a large number of traffic sign samples across the different classes.

## 🔎 Key Findings

- The CNN was able to learn useful visual features from traffic sign images.
- Model accuracy improved significantly during training.
- The final test accuracy reached **95.19%**.
- Most traffic sign classes were classified with high precision and recall.
- Some visually similar or less represented classes were more difficult for the model to distinguish.

## 📁 Repository Structure

```text
traffic-sign-recognition-cnn/
│
├── traffic_sign_recognition_cnn.ipynb
├── README.md
└── requirements.txt
