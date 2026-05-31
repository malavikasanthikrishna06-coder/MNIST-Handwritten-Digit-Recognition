# MNIST Handwritten Digit Recognition Engine

An end-to-end Computer Vision project that trains a Convolutional Neural Network (CNN) to recognize handwritten digits ($0$-$9$) with high precision using PyTorch and the MNIST dataset.

---

## 📊 Project Results
* **Final Test Accuracy:** 98.50% (Continuous single-cell execution pipeline) | *Peak run: 99.14%* on 10,000 unseen test images.
* **Architecture:** 2 Convolutional Layers (`Conv2d`) + Max Pooling + 2 Fully Connected Layers.
* **Optimization:** Adam Optimizer ($lr=0.001$) with Cross-Entropy Loss.

---

## 🧠 Neural Network Architecture Breakdown
The network processes grayscale image matrices ($1 \times 28 \times 28$) through the following pipeline:
1. **Convolutional Layer 1:** 32 filters, kernel size 3, padding 1 (Extracts structural edge features).
2. **Max Pooling & ReLU Activation:** Reduces spatial dimensions while preserving dominant features.
3. **Convolutional Layer 2:** 64 filters, kernel size 3, padding 1 (Extracts complex geometric patterns).
4. **Fully Connected Layers:** Flattens the feature maps into a 128-node dense layer, outputting a final 10-dimensional class probability vector.

---

## 🚀 How to Run

1. Open the `.ipynb` notebook in Google Colab or Jupyter Notebooks.
2. If using a GPU environment, ensure the `.cuda()` transitions match your hardware accelerator settings.
3. Run the consolidated code block sequentially to fetch the dataset, initialize the parameters, execute the 3-epoch training loop, and evaluate test performance.
