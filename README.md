# MLOps: MNIST Handwritten Digit Predictor

A PyTorch implementation of a Feedforward Neural Network (ANN) designed to predict handwritten digits from the MNIST dataset, prepared with performance tracking and MLOps principles.

## ✨ Highlights
* **High Accuracy:** Achieves **~97.5%** test accuracy in 3 epochs.
* **Overfitting Check:** Tracked real-time Loss & Accuracy metrics to ensure a strong **Good Fit**.
* **Hardware Ready:** Automatically leverages GPU (CUDA) acceleration when available.
* **Model Persistence:** Exports final trained weights as `model.pth`.

## 🧬 Architecture
* **Input Layer:** $784$ features (Flattened $28 \times 28$ image)
* **Hidden Layers:** $784 \to 677 \to 590$ (ReLU activation)
* **Output Layer:** $10$ classes (Digits 0–9)

## 📊 Evaluation Summary
* **Train Accuracy:** ~98.2%
* **Test Accuracy:** 97.5%
* **Model Status:** **Good Fit** (Minimal gap between train and test metrics).
