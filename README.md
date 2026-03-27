# Boat Image Classification using CNN

## 📌 Project Overview

This project builds a Convolutional Neural Network (CNN) to classify different types of boats from images.

It demonstrates the complete machine learning workflow, including data preprocessing, model training, and evaluation.

---

## 📂 Dataset

The dataset contains images of various boat categories.

* The training data initially consisted of images and a ground truth file.
* Images were reorganized into class-specific folders using their labels.

---

## ⚙️ Approach

### 1. Data Preprocessing

* Rescaling image pixel values
* Data augmentation (rotation, flipping, shifting)
* Splitting dataset into training and validation sets

### 2. Model Building

* Convolutional layers for feature extraction
* MaxPooling layers for dimensionality reduction
* Dense layers for classification
* Dropout to reduce overfitting

### 3. Training

* Loss function: Categorical Crossentropy
* Optimizer: Adam
* Evaluation metric: Accuracy

---

## 📊 Results

* Training Accuracy: ~90%
* Validation Accuracy: ~68%
* Observed slight overfitting after several epochs

---

## 🧠 Key Learnings

* Importance of proper data preprocessing
* Handling real-world dataset inconsistencies
* Building and training CNN models
* Debugging machine learning pipelines

---

## 🛠 Tools Used

* Python
* TensorFlow / Keras
* Google Colab

---

## 📦 Model Download

The trained CNN model can be accessed here:

👉 [Download Model] (https://drive.google.com/file/d/1IXfeEz2kDPj_qygOGlFljimPlUWHP0PO/view?usp=drive_link)

## 👤 Author

Egwurube Daniel Alex

