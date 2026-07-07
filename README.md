# Fish Species Classification using Convolutional Neural Networks (CNN)

## Project Overview

This project was developed as part of the **Machine Learning** course in the **Master of Science in Data Science** program at the **University of Europe for Applied Sciences**.

The project presents an automated fish species classification system using Deep Learning. Two image classification models were implemented and compared:

- Custom Convolutional Neural Network (CNN)
- MobileNetV2 Transfer Learning Model

The models were trained and evaluated using the **A Large Scale Fish Dataset** available on Kaggle.

---

# Objectives

- Develop a Custom CNN model for fish species classification.
- Implement transfer learning using MobileNetV2.
- Compare the performance of both models.
- Evaluate classification performance using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

# Dataset

**Dataset Name**

A Large Scale Fish Dataset

**Source**

https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset

**Dataset Statistics**

- Total Images: 9,000
- Number of Classes: 9
- Image Size: 224 × 224
- Image Format: JPG

Fish Species:

- Black Sea Sprat
- Gilt-Head Bream
- Horse Mackerel
- Red Mullet
- Red Sea Bream
- Sea Bass
- Shrimp
- Striped Red Mullet
- Trout

---

# Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# Models Implemented

## 1. Custom CNN

Performance

- Training Accuracy: **91.76%**
- Validation Accuracy: **98.08%**
- Test Accuracy: **97.48%**

---

## 2. MobileNetV2 (Transfer Learning)

Performance

- Training Accuracy: **88.32%**
- Validation Accuracy: **97.56%**
- Test Accuracy: **96.89%**

---

# Model Comparison

| Model | Test Accuracy |
|--------|---------------|
| Custom CNN | **97.48%** |
| MobileNetV2 | **96.89%** |

The Custom CNN achieved the highest overall classification accuracy on the test dataset.

---

# Results

The project generated the following outputs:

- Training and Validation Accuracy Curves
- Training and Validation Loss Curves
- Confusion Matrix
- Classification Report
- Model Comparison Chart

These figures are available in the **images/** folder.

---

# How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/harshavardhib/Fish-Species-Classification-CNN.git
```

## 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

## 3. Download the Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset

Place the dataset in the appropriate directory or attach it to the Kaggle Notebook.

## 4. Open the Notebook

Run:

```
fish-species-classification-cnn.ipynb
```

## 5. Execute All Cells

Run the notebook from top to bottom to:

- Load the dataset
- Preprocess images
- Train the Custom CNN
- Train MobileNetV2
- Evaluate both models
- Generate plots and performance metrics

---

# Kaggle Notebook

Kaggle Notebook: [https://www.kaggle.com/code/harshavardhii/fish-species-classification-cnn]

---

# Pre-trained Models

The trained model files are not included in this repository because they exceed GitHub's file size limit (100 MB).

They can be downloaded from Google Drive:

- **Custom CNN Model (.keras):** [https://drive.google.com/file/d/1Ect-qPm-sGLqzhUL5NcmvGIHT0b7-In0/view?usp=drive_link]
- **MobileNetV2 Model (.keras):** [https://drive.google.com/file/d/1f8Z4_bV_nBPszQImfwbzwMq7B7th7elw/view?usp=drive_link]

---

# Repository Structure

```
Fish-Species-Classification-CNN/
│
├── fish-species-classification-cnn.ipynb
├── README.md
├── requirements.txt
├── dataset_link.txt
├── LICENSE
├── .gitignore
│
└── images/
    ├── custom_learning_curves.png
    ├── custom_confusion_matrix.png
    ├── mobilenet_learning_curves.png
    ├── mobilenet_confusion_matrix.png
    └── model_comparison.png
```

---

# Future Improvements

- Implement EfficientNet and ResNet architectures.
- Apply advanced data augmentation techniques.
- Deploy the trained model as a web application.
- Optimize the model for real-time fish species recognition.

---

# Author

**Harshavardhan Babu Bokka**

Master of Science in Data Science

University of Europe for Applied Sciences

---

# License

This project is licensed under the MIT License.
