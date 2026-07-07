# Fish-Species-Classification-CNN
Master's Data Science project implementing a Custom CNN and MobileNetV2 for fish species classification using TensorFlow and Keras.
# Fish Species Classification using Convolutional Neural Networks (CNN)

## Project Overview

This project presents a deep learning-based image classification system for automatic fish species recognition. A Custom Convolutional Neural Network (CNN) and the MobileNetV2 transfer learning model were implemented and compared using a large-scale fish image dataset.

---

## Objectives

- Develop a Custom CNN model for fish species classification.
- Apply transfer learning using MobileNetV2.
- Compare model performance.
- Evaluate classification accuracy using multiple metrics.

---

## Dataset

**Dataset Name:**
A Large Scale Fish Dataset

**Source:**
https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset

Images:
9000

Classes:
9 Fish Species

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## How to Run

1. Clone the repository.

git clone https://github.com/harshavardhib/Fish-Species-Classification-CNN.git

2. Install the required packages.

pip install -r requirements.txt

3. Download the dataset from Kaggle:
https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset

4. Open the notebook:

fish-species-classification-cnn.ipynb

5. Run all notebook cells sequentially.

---

## Models

### Custom CNN

- Training Accuracy: 91.76%
- Validation Accuracy: 98.08%
- Test Accuracy: 97.48%

### MobileNetV2

- Training Accuracy: 88.32%
- Validation Accuracy: 97.56%
- Test Accuracy: 96.89%

---
## Pre-trained Models

The trained model files are not included in this repository because they exceed GitHub's file size limit (100 MB).

They can be downloaded from Google Drive:

- **Custom CNN Model (.keras):** [DRIVE LINK](https://drive.google.com/file/d/1Ect-qPm-sGLqzhUL5NcmvGIHT0b7-In0/view?usp=drive_link)
- **MobileNetV2 Model (.keras):** [DRIVE LINK](https://drive.google.com/file/d/1f8Z4_bV_nBPszQImfwbzwMq7B7th7elw/view?usp=drive_link)

## Results

| Model | Test Accuracy |
|--------|--------------:|
| Custom CNN | 97.48% |
| MobileNetV2 | 96.89% |

The Custom CNN achieved the best overall performance.

---

## Repository Structure

```text
Proposal.pdf
Fish_Species_Classification.ipynb
requirements.txt
dataset/
figures/
README.md
```

---

## Author

Harsha Vardhi

Master of Science in Data Science

University of Europe for Applied Sciences
