# MLops
MNIST Handwritten Digit Predictor
A simple PyTorch implementation of a Feedforward Neural Network (ANN) designed to predict handwritten digits from the MNIST dataset.
FeaturesHigh Accuracy: Reaches 96.92% accuracy in only 3 epochs.Hardware Ready: Supports GPU (CUDA) acceleration automatically.Visual Validation: Plots test images showing True vs Predicted labels using Matplotlib (Green for correct, Red for incorrect).Model Saving: Saves trained weights as model.pth.
Model ArchitectureInput: Flattened $28 \times 28$ images ($784$ pixels)Hidden Layers: $784 \to 677 \to 590$ (with ReLU activation)Output: $10$ classes (digits 0–9)
