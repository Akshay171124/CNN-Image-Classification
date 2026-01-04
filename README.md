# 🖼️ Image Classification using CNN

This project implements an image classification pipeline using a **Convolutional Neural Network (CNN)** on the **CIFAR-10 dataset**.  
It includes data preprocessing, CNN model construction, training, and evaluation.

---

## 📁 Project Structure

~~~
Image_Classification/
├── CNN_build/
│   └── cnn.py
├── Preprocessing/
│   └── format.py
├── testing/
│   └── execute.py
└── README.md
~~~

---

## 📌 Dataset
- CIFAR-10 (10 classes, 60,000 images)
- Image size: 32×32×3
- Loaded using `keras.datasets.cifar10`

---

## ⚙️ Workflow
- Data preprocessing and normalization (`format.py`)
- CNN model definition (`cnn.py`)
- Training and evaluation (`execute.py`)

---

## ▶️ How to Run

~~~
pip install tensorflow keras numpy
python testing/execute.py
~~~

---

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy

---

## 👤 Contributor
- **Akshay Prajapati** — https://github.com/Akshay171124

---

## 📜 Notes
For academic and learning purposes.
