
# 🧠 MNIST Handwritten Digit Recognition Engine

An end-to-end Computer Vision project that trains a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) with high accuracy using PyTorch and the MNIST dataset.

---

## 📊 Project Results

* **Final Test Accuracy:** 99.09%
* **Dataset:** MNIST (70,000 handwritten digit images)
* **Architecture:** 2 Convolutional Layers + Max Pooling + 2 Fully Connected Layers
* **Optimizer:** Adam (Learning Rate = 0.001)
* **Loss Function:** Cross-Entropy Loss

---

## 🛠️ Tech Stack

* Python
* PyTorch
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## 🧠 Model Architecture

The CNN processes grayscale images of size **1 × 28 × 28** through the following layers:

1. Convolution Layer (32 Filters)
2. ReLU Activation
3. Max Pooling
4. Convolution Layer (64 Filters)
5. ReLU Activation
6. Max Pooling
7. Fully Connected Layer (128 Neurons)
8. Output Layer (10 Classes)

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/malavikasanthikrishna06-coder/MNIST-Handwritten-Digit-Recognition.git
cd MNIST-Handwritten-Digit-Recognition
```

### 2. Install Dependencies

```bash
pip install torch torchvision numpy matplotlib scikit-learn
```

### 3. Run the Project

Open the notebook in Google Colab or Jupyter Notebook and run all cells sequentially.

The model will:

* Download the MNIST dataset
* Train the CNN model
* Evaluate test accuracy
* Generate predictions on unseen images
* Save the trained model

---

## 📈 Performance

**Test Accuracy:** 99.09%

The trained CNN demonstrates excellent performance on unseen handwritten digit images from the MNIST test dataset.

---

## 📸 Sample Predictions

<img width="950" height="412" alt="image" src="https://github.com/user-attachments/assets/68c5d729-55e8-4985-8bfa-43171385c6a6" />


---

## 👨‍💻 Features

* CNN-based handwritten digit classification
* Automated MNIST dataset download
* Model evaluation on unseen test data
* Sample prediction visualization
* Trained model saving using PyTorch

---

## 📚 Dataset

The project uses the MNIST dataset, containing 70,000 grayscale handwritten digit images (28×28 pixels) across 10 digit classes (0–9).

