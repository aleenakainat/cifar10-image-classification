# cifar10-image-classification
CIFAR-10 image classification using a CNN (CPU-only training). Includes accuracy/loss graphs, predictions, and confusion matrix.
# CIFAR-10 Image Classification (CPU-Only)

**CIFAR-10 image classification using a Convolutional Neural Network (CNN), trained entirely on CPU.**  
Includes accuracy & loss graphs, sample predictions, and a confusion matrix — optimized for limited hardware usage.

---

## 📝 Overview

This project demonstrates how to build, train, and evaluate a CNN model on the CIFAR-10 dataset without relying on GPU. It is tailored for scenarios where GPU resources are unavailable.  
Key parts:

- Data normalization and visualization  
- Model architecture design  
- Training and validation process  
- Model evaluation with visual outputs  
- Sample predictions on test images  

---

## 🛠 Tools & Libraries

| Purpose | Library / Framework |
|---|---|
| Neural networks / model building | TensorFlow / Keras |
| Numeric operations / array handling | NumPy |
| Plotting / Visualizations | Matplotlib |
| Confusion Matrix & Metrics | scikit-learn |

---

## 📊 Dataset & Preprocessing

- Dataset: CIFAR-10 (60,000 32×32 color images in 10 classes)  
- Preprocessing steps:
  - Normalize pixel values to [0, 1] range  
  - One-hot or sparse labels depending on setup  
  - Train / validation split supplied by the dataset

---

## 🧠 Model Architecture

- Three convolutional layers + MaxPooling layers  
- Flatten + Dense hidden layer  
- Final Dense layer with softmax activation for classification into 10 classes

---

## ⚙ Training Details

- Training on CPU  
- Number of epochs: **5** (you may increase later if time allows)  
- Batch size: 64  
- Loss function: sparse categorical crossentropy  
- Optimizer: Adam  

---

## 📈 Results & Visualizations

Test Accuracy: *approximate value that your model got* (edit with your actual value)  
Loss & Accuracy plots: training vs validation curves  

### Sample Outputs

Below are some visual examples (replace file names according to your repo structure):

![Accuracy & Loss Plot](sample_outputs/accuracy_plot.png)  
![Confusion Matrix](sample_outputs/confusion_matrix.png)  
![Sample Predictions](sample_outputs/predictions.png)

---

## ▶ Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/cifar10-image-classification.git

