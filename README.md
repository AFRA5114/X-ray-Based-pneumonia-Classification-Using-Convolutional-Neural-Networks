# X-ray-Based-pneumonia-Classification-Using-Convolutional-Neural-Networks
Built a CNN-based model to detect pneumonia from chest X-ray images using TensorFlow/Keras. Performed data preprocessing, augmentation, and model training, and evaluated performance using accuracy metrics and visualizations to support reliable medical image classification.


# 🩺 X-ray Based Pneumonia Classification using CNN

## 📌 Project Overview

This project focuses on detecting **Pneumonia** from chest X-ray images using a **Convolutional Neural Network (CNN)**. The model is trained to classify images into **Normal** and **Pneumonia** categories, helping in early diagnosis and medical decision support.

---

## 🎯 Objective

* Build a deep learning model for **image classification**
* Detect pneumonia from X-ray images with high accuracy
* Understand patterns in medical imaging using CNN

---

## 📂 Dataset

* **Dataset Type:** Medical Image Dataset (Chest X-rays)

* **Classes:**

  * Normal
  * Pneumonia

* **Dataset Source:**
  👉 https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

* **Dataset Structure:**

```
chest_xray/
    train/
        NORMAL/
        PNEUMONIA/
    test/
        NORMAL/
        PNEUMONIA/
    val/
        NORMAL/
        PNEUMONIA/
```

---

## 🛠️ Tools & Technologies Used

* **Programming Language:** Python 🐍

* **Libraries & Frameworks:**

  * TensorFlow / Keras
  * NumPy
  * Matplotlib
  * OpenCV

* **Platform:** Google Colab / Jupyter Notebook

---

## ⚙️ Model Architecture

* Convolutional Layers (Feature Extraction)
* MaxPooling Layers
* Fully Connected (Dense) Layers
* Activation Functions: ReLU, Softmax
* Loss Function: Categorical Crossentropy
* Optimizer: Adam

---

## 📊 Data Visualization & Insights

### 🔍 Key Observations:

* Pneumonia X-rays show **white patches (lung infection areas)** compared to normal lungs
* Dataset is slightly **imbalanced**, requiring careful training
* Data augmentation helps improve model performance

### 📈 Visualizations Included:

* Sample X-ray images (Normal vs Pneumonia)
* Training vs Validation Accuracy graph
* Training vs Validation Loss graph

---

## 🔄 Workflow

1. Data Collection
2. Data Preprocessing (Resizing, Normalization)
3. Data Augmentation
4. Model Building (CNN)
5. Model Training
6. Model Evaluation
7. Prediction on Test Images

---

## 📉 Model Performance

* Achieved good accuracy on validation data
* Reduced overfitting using augmentation and dropout

*(Add your exact accuracy here if available)*

---

## 🚀 How to Run the Project

```bash
# Clone repository
git clone https://github.com/your-username/pneumonia-classification.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```

---

## 📌 Future Improvements

* Use Transfer Learning (ResNet, VGG16)
* Improve dataset balance
* Deploy model using Flask / Streamlit
* Integrate into healthcare applications

---

