# **Handwritten Digit Recognition using ANN & CNN on the MNIST Dataset**

## **Overview**
This project focuses on recognizing handwritten digits using the **MNIST dataset**, which consists of **70,000 grayscale images** of digits (0-9). Two machine learning models are implemented and compared:

- **Artificial Neural Network (ANN)** - A fully connected neural network that processes the pixel values of each digit image.
- **Convolutional Neural Network (CNN)** - A deep learning model optimized for image classification, using convolutional and pooling layers to extract features.

## **Technologies Used**
- **Programming Language**: Python  
- **Libraries**:  
  - **TensorFlow/Keras** - Model development and training  
  - **NumPy & Pandas** - Data handling and preprocessing  
  - **Matplotlib** - Data visualization  
  - **Scikit-learn** - Model evaluation  

## **Model Performance**
| **Model** | **Accuracy** | **Precision** | **Recall** | **F1-Score** |
|-----------|-------------|--------------|------------|--------------|
| **ANN** | ~98% | **0.97** | **0.97** | **0.97** |
| **CNN** | ~99.3% | **0.99** | **0.99** | **0.99** |


The **CNN model demonstrated superior performance** over ANN in handwritten digit classification, highlighting the power of convolutional layers in extracting meaningful patterns from images.
