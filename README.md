# 😷 Real-Time Face Mask Detection

A computer vision application that detects faces in real-time using a webcam and classifies whether the person is wearing a face mask or not using a deep learning model.

---

## 🚀 Features

> Key highlights of the application.

- Real-time face detection using OpenCV
- Mask vs No Mask classification using CNN
- Works with webcam video feed
- Easy-to-train with your own dataset

---

## 🧠 Model Architecture

> Structure of the neural network model used.

- **Input:** Face region of interest (ROI)
- **Base Model:** MobileNetV2 (for transfer learning)
- **Classifier:** Fully connected layers
- **Output:** Binary class — Mask / No Mask

---

## 📦 Installation

> Steps to set up the environment and install dependencies.

```bash

pip install -r requirements.txt

---

## 🛠️ Technologies Used

> Tools and libraries powering this project.

- **Python** — Core programming language
- **OpenCV** — For face detection and video processing
- **TensorFlow / Keras** — Deep learning model
- **NumPy** — Numerical operations
- **Matplotlib** — Visualization (optional for analysis)

---

## 📊 Performance

> Model evaluation metrics on validation/test dataset.

| Metric     | Value      |
|------------|------------|
| Accuracy   | 98%        |
| Precision  | 97%        |
| Recall     | 98%        |
