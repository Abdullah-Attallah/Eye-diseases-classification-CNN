# 👁️ Eye Diseases Classification using CNN & EfficientNetB3

## 📌 Project Overview
This project focuses on **automatic eye disease classification** from medical images using **Deep Learning**. It leverages **Convolutional Neural Networks (CNNs)** and **EfficientNetB3** to learn visual patterns associated with different eye conditions, supporting early diagnosis and decision-making in healthcare systems.

The model is trained and evaluated using a structured image dataset split into training, validation, and testing sets.

---

## 🎯 Objectives
- Build a deep learning model to classify eye diseases from images  
- Compare traditional CNN performance with **EfficientNetB3**
- Apply best practices in data preprocessing, augmentation, and evaluation
- Achieve high accuracy while maintaining generalization

---

## 🧠 Models Used

### 1. Convolutional Neural Network (CNN)
A custom CNN architecture designed to:
- Extract hierarchical spatial features from eye images  
- Learn disease-specific visual patterns  

### 2. EfficientNetB3 (Transfer Learning)
EfficientNetB3 is used to:
- Achieve a strong accuracy–efficiency tradeoff  
- Reduce computational cost compared to larger architectures  
- Improve performance on medical imaging tasks  

Pretrained **ImageNet** weights are used and fine-tuned on the eye disease dataset.

---

## 🗂️ Dataset
- Image-based dataset organized in directory format  
- Each folder represents a specific eye disease class  
- Dataset is split into:
  - **Training set**
  - **Validation set**
  - **Test set**

Images are resized and normalized to match the input requirements of the models.

---

## ⚙️ Data Preprocessing & Augmentation
- Image resizing  
- Pixel normalization  
- Data augmentation (rotation, flipping, zooming)  
- Label encoding for multi-class classification  

These steps help improve generalization and reduce overfitting.

---

## 📊 Evaluation Metrics
Model performance is evaluated using:
- **Accuracy**
- **Training & Validation Loss**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score)**

---

## 🛠️ Technologies & Libraries
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/Abdullah-Attallah/Eye-diseases-classification-CNN.git
