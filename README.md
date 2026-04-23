# 🧠 Handwritten Digit Classifier (MNIST) using TensorFlow

##  Overview

This project is a simple deep learning-based handwritten digit classifier built using TensorFlow and Keras. It uses the famous MNIST dataset to recognize digits (0–9) from grayscale images.

The model is a basic Artificial Neural Network (ANN) with fully connected layers.

--

##  Features

* Uses MNIST dataset (built-in with Keras)
* Preprocessing with normalization
* Simple and efficient ANN model
* Achieves ~97.6% accuracy
* Beginner-friendly implementation

---

##  Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Scikit-learn

---

##  Dataset

The dataset used is **MNIST**, which contains:

* 60,000 training images
* 10,000 testing images
* Image size: 28x28 (grayscale)

---

##  Model Architecture

* Flatten Layer (28x28 → 784)
* Dense Layer (128 neurons, ReLU activation)
* Output Layer (10 neurons, Softmax activation)

Total Parameters: **101,770**

---

##  Installation

```bash
pip install tensorflow scikit-learn numpy
```

---

##  How to Run

```bash
python your_script_name.py
```

---

##  Workflow

1. Load MNIST dataset
2. Normalize pixel values (0–255 → 0–1)
3. Build Sequential Neural Network
4. Train model with training data
5. Validate using validation split
6. Predict on test data
7. Evaluate accuracy

---

## 📊 Results

* Training Loss ↓ over epochs
* Validation Loss stabilizes
* Test Accuracy: **97.65%**

---

##  Sample Output

The model predicts digits correctly for most handwritten inputs.

---

##  Future Improvements

* Use CNN for better accuracy
* Add dropout to prevent overfitting
* Build a web app using Streamlit
* Deploy model as an API

---

##  Contribution

Feel free to fork this repository and improve the model or UI.

---

## 📜 License

This project is open-source and free to use.
