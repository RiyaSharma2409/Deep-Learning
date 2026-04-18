# 🐶🐱 Cat vs Dog Image Classification using CNN

## 🚀 Overview
This project implements a Convolutional Neural Network (CNN) to classify images of cats and dogs.

It demonstrates how deep learning models can extract spatial features from images and perform accurate classification.

---

## 📊 Dataset
- Image dataset with two classes:
  - Cats
  - Dogs
- Structured into:
  - Training set
  - Test set

---

## ⚙️ Approach

### 🔹 Data Preprocessing
- Image resizing to 64x64
- Feature scaling (rescaling pixel values)
- Data augmentation:
  - Rotation
  - Zoom
  - Horizontal flip

---

### 🔹 Model Architecture

1. Convolution Layer (32 filters, 3x3)
2. Max Pooling (2x2)
3. Convolution Layer (32 filters)
4. Max Pooling
5. Flattening
6. Fully Connected Layer (128 neurons)
7. Output Layer (Sigmoid)

---

## 🧠 Key Concepts Used
- Convolutional Neural Networks (CNN)
- Image Augmentation
- Feature Extraction
- Binary Classification

---

## 📈 Training
- Optimizer: Adam  
- Loss: Binary Crossentropy  
- Epochs: 25  

---

## 🔍 Prediction
The model predicts whether a given image is:
- Cat 🐱
- Dog 🐶

---

## 🧠 Insights
- CNN automatically extracts spatial features (edges, shapes, textures)
- Data augmentation helps prevent overfitting
- Pooling reduces computation and improves generalization

---

## ⚠️ Challenges Faced
- Dataset path issues (`dataset/training_set`)  
- Image preprocessing consistency  
- Model tuning (filters, layers)

---

## 🏆 Conclusion
CNNs are highly effective for image classification tasks and outperform traditional ML methods in handling visual data.
