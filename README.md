# MNIST Digit Classifier 🧠🔢

This project is a basic digit classification system using the **MNIST dataset**, implemented in a Jupyter notebook using TensorFlow and Keras.

---

## 📁 Files in This Repository
| File              | Description                                  |
|-------------------|----------------------------------------------|
| `mnist.ipynb`     | Jupyter notebook with model training code    |
| `mnist_model.keras` | Trained Keras model file (saved in `.keras` format) |

---

## 🚀 What It Does
- Loads the MNIST dataset (70,000 handwritten digits from 0–9)
- Preprocesses the data (normalization & reshaping)
- Builds a simple **CNN** or **Dense Neural Network**
- Trains the model and evaluates accuracy
- Saves the model to disk for later use

---

## ✅ Accuracy
The model achieves high accuracy (~98%) on the test dataset due to the simplicity and cleanliness of the MNIST dataset.

---

## 🛠️ How to Run
```bash
pip install tensorflow numpy matplotlib
