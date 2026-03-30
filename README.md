# 🧠 CIFAR-10 Image Classification using CNN

## 🚀 Overview

This project focuses on building a **Convolutional Neural Network (CNN)** to classify images from the CIFAR-10 dataset into 10 different categories.

The project demonstrates a complete deep learning pipeline including **data preprocessing, model building, training, optimization, and evaluation**.

---

## 📊 Dataset

* **Dataset:** CIFAR-10
* **Total Images:** 60,000
* **Image Size:** 32 × 32 (RGB)
* **Classes:**

  * Airplane ✈️
  * Automobile 🚗
  * Bird 🐦
  * Cat 🐱
  * Deer 🦌
  * Dog 🐶
  * Frog 🐸
  * Horse 🐴
  * Ship 🚢
  * Truck 🚚

---

## 🧠 Model Architecture

The model uses a **deep CNN with multiple convolutional blocks**:

* Conv2D + Batch Normalization
* Conv2D + Batch Normalization
* MaxPooling
* Dropout

Repeated for multiple blocks with increasing filters (32 → 64 → 128)

### 🔹 Fully Connected Layers:

* Dense (256 neurons)
* Batch Normalization
* Dropout
* Output layer (Softmax)

---

## ⚙️ Techniques Used

### 🔹 Data Preprocessing

* Normalization (0–255 → 0–1)

### 🔹 Data Augmentation

* Rotation
* Width/Height shift
* Zoom
* Horizontal flip

### 🔹 Regularization

* Dropout
* Batch Normalization

### 🔹 Optimization

* Adam optimizer
* Reduced learning rate (0.0005)

### 🔹 Callbacks

* EarlyStopping (prevents overfitting)
* ReduceLROnPlateau (dynamic learning rate adjustment)

---

## 📈 Training Strategy

* Batch size: 32
* Epochs: Up to 30 (with early stopping)
* Validation monitoring for performance tracking

---

## 📊 Results

| Metric              | Value          |
| ------------------- | -------------- |
| Training Accuracy   | ~82–83%        |
| Validation Accuracy | **~84–85% 🚀** |
| Best Epoch          | ~22            |

---

## 💡 Key Learnings

* Data augmentation significantly improves generalization
* Batch normalization stabilizes training
* Learning rate scheduling improves convergence
* Early stopping prevents overfitting
* Deeper CNN architectures extract better features

---

## 🛠️ Tech Stack

* Python 🐍
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📁 Project Structure

```
CIFAR10-CNN/
│
├── notebooks/
├── models/
├── results/
└── README.md
```

---

## 🚀 Future Improvements

* Try transfer learning (ResNet, MobileNet)
* Hyperparameter tuning
* Deploy model using Flask/Django
* Add confusion matrix visualization

---

## 🙌 Conclusion

This project demonstrates a complete **end-to-end deep learning workflow**, progressing from a basic CNN to an optimized model achieving **~85% accuracy** on CIFAR-10.

---

## ⭐ If you found this useful

Give it a ⭐ and feel free to connect!
