# 🗑️ Garbage Classification – Week 1

This repository contains the Week 1 deliverables for the **Shell-Edunet Skills4Future Internship Project – Garbage Classification**.

## 📌 Objective

To develop a Convolutional Neural Network (CNN) model that classifies garbage images into six categories:
- **Cardboard**
- **Glass**
- **Metal**
- **Paper**
- **Plastic**
- **Trash**

## 📂 Dataset

- The dataset was provided in `.zip` format containing labeled folders for each garbage category.
- It was uploaded to **Google Drive**, extracted, and used via **Google Colab**.

## 🧠 Model Architecture

A custom CNN model was built using:
- `Conv2D`, `MaxPooling2D`
- `Dropout`, `Flatten`, `Dense` layers
- ReLU and softmax activation functions

> ✅ Image input size: `(128, 128, 3)`

## 🏗️ Workflow

1. **Mount Google Drive**
2. **Extract dataset**
3. **Create image generators for training & validation**
4. **Build and compile CNN model**
5. **Train model and visualize accuracy**
6. **Evaluate on validation data**
7. **Save trained model as `.h5`**

## 📈 Performance

- **Validation Accuracy**: ~65%
- **Loss**: 1.56 (on validation set)

## 💾 Files Included

- `Week1_Garbage_Classification.ipynb`: Google Colab notebook
- `garbage_classifier_model.h5`: Trained model
- `README.md`: Project documentation
- `improvisations.txt`: Ideas for improvement (Week 2)

## 📌 Tools & Libraries

- Python, TensorFlow, Keras
- Matplotlib, NumPy, Google Colab

## 📌 Key Takeaways

- Understood the pipeline of training a deep learning model
- Preprocessed real-world image data
- Visualized model performance with accuracy/loss plots
- Saved and exported a trained `.h5` model for later use

---

### 🚀 Next Step (Week 2)
The trained model will be used in Week 2 to classify custom uploaded images and test generalization.

