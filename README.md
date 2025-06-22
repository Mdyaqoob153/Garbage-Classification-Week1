# Garbage Classification - Week 1 (Shell-Edunet Internship)

This is the Week 1 submission for the Shell-Edunet Skills4Future Internship (Project P4: Garbage Classification). The goal is to classify garbage images into multiple categories using a Convolutional Neural Network (CNN) model.

## 📁 Files in this Repository

- `garbage_classification_week1.ipynb` - Jupyter Notebook containing the full model building, training, and evaluation.
- `garbage_classifier_model.h5` - The trained CNN model file.
- `.gitattributes` - Git LFS tracking for large files.

## 📊 Dataset

The dataset used consists of garbage images organized into different categories like paper, metal, plastic, etc.

## 🧠 Model Details

- **Architecture:** CNN (Convolutional Neural Network)
- **Framework:** TensorFlow/Keras
- **Accuracy Achieved:** *[mention final accuracy here]*

## 🛠️ How to Use

1. Clone the repository:


2. Open the notebook in Google Colab or Jupyter.
3. Run the cells to understand the pipeline and predictions.
4. Load the model using:
```python
from keras.models import load_model
model = load_model('garbage_classifier_model.h5')
