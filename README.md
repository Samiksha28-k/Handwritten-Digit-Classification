# Handwritten-Digit-Classification
# ✍️ Handwritten Digit Classification using CNN & RNN

## 📌 Project Overview

This project focuses on recognizing handwritten digits (0–9) using deep learning techniques. The goal is to build and compare two models: a Convolutional Neural Network (CNN) and a Recurrent Neural Network (RNN) for accurate digit classification.

---

## 📂 Dataset

We use the **MNIST Dataset**, a widely used benchmark dataset for image classification tasks.

### Dataset Details:

* Total Images: 70,000
* Training Images: 60,000
* Testing Images: 10,000
* Image Size: 28 × 28 pixels
* Color: Grayscale
* Classes: 10 (digits 0–9)

---

## 🎯 Problem Statement

Handwritten digit recognition is an important problem in computer vision with applications in:

* Postal automation
* Bank cheque processing
* Document digitization

Traditional methods require manual feature extraction. This project uses deep learning models to automatically learn features and improve performance.

---

## 🧠 Models Used

### 1️⃣ Convolutional Neural Network (CNN)

* Extracts spatial features from images
* Uses convolution, pooling, and fully connected layers
* Achieves high accuracy on image data

### 2️⃣ Recurrent Neural Network (RNN)

* Treats images as sequences (row-wise)
* Learns sequential patterns in the data
* Useful for understanding dependencies in sequences

---

## ⚙️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib (optional for visualization)

---

## 🚀 Project Workflow

1. Load MNIST dataset
2. Preprocess images (normalization & tensor conversion)
3. Build CNN and RNN models
4. Train models using training data
5. Evaluate models on test data
6. Compare performance using accuracy

---

## 📊 Performance Metrics

* **Accuracy**
* **Confusion Matrix**

---

## 📈 Expected Results

* CNN Accuracy: ~97–99%
* RNN Accuracy: ~95–97%

CNN generally performs better due to its ability to capture spatial features.

---

## 📌 Applications

* Handwritten digit recognition
* Bank cheque processing
* ZIP/postal code reading
* Form automation systems

---

## 🔮 Future Improvements

* Use advanced models like CNN + LSTM
* Hyperparameter tuning
* Data augmentation
* Deploy model using web app

---

## 👩‍💻 Author

Samiksha Sengar

---

## ⭐ Conclusion

This project demonstrates how deep learning models like CNN and RNN can be used for handwritten digit classification. CNN provides higher accuracy due to better feature extraction, while RNN offers a different approach by handling sequential data.
