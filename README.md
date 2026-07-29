# MRI-Based-Brain-Tumor-Classification-Using-Convolutional-Neural-Networks

## 📌 Project Overview

This project focuses on detecting brain tumors from MRI scan images using a Convolutional Neural Network (CNN). The model classifies MRI images into tumor and non-tumor categories, assisting in early diagnosis through automated image classification.

---

## 📂 Dataset

- Source: Kaggle Brain Tumor MRI Dataset
- Image Type: MRI Brain Images
Classes:
    - Glioma Tumor
    - Meningioma Tumor
    - Pituitary Tumor
    - No Tumor
- Image Format: JPG/PNG
- Total Images: (Update based on your dataset)

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn


---

## 🧹 Data Preprocessing

- Loaded MRI images
- Resized images to a fixed input size
- Normalized pixel values
- Encoded class labels
- Split data into training, validation, and testing sets
- Applied image augmentation to improve model generalization

---

## 📊 Data Visualization

Performed visualization to understand the dataset:

- Sample MRI images
- Tumor vs No Tumor class distribution
- Image dimensions
- Training and validation accuracy
- Training and validation loss
- Prediction results on test images

Visualization Techniques:

- Image Grid
- Count Plot
- Accuracy Curve
- Loss Curve
- Prediction Visualization

---

## 🤖 CNN Model Architecture

The CNN model consists of:

- Convolutional Layers
- ReLU Activation
- Max Pooling Layers
- Dropout Layers
- Flatten Layer
- Dense Layers
- Softmax/Sigmoid Output Layer

---

## 📏 Model Evaluation

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 🚀 Project Workflow

1. Dataset Collection
2. Image Preprocessing
3. Data Augmentation
4. CNN Model Development
5. Model Training
6. Model Evaluation
7. Prediction on Test Images

---

## 📌 Key Insights

- CNN effectively learns spatial features from MRI images.
- Data augmentation improves model generalization.
- The trained model achieves high classification accuracy.
- Deep learning enables automated brain tumor detection with minimal manual intervention.

---

## 📁 Repository Structure

Brain-Tumor-Detection/
│
├── dataset/
├── notebooks/
├── models/
├── images/
├── README.md
├── requirements.txt
└── predictions/

---

## 📬 Future Improvements

- Deploy the model using Streamlit or Flask
- Improve accuracy using Transfer Learning (ResNet50, EfficientNet)
- Integrate Grad-CAM for model explainability
- Support multi-class brain tumor classification
- Deploy as a web application for real-time predictions

