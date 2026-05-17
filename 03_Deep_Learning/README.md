# Deep Learning & Neural Networks

Deep Learning is a subset of ML based on Artificial Neural Networks, inspired by the human brain. It excels at complex tasks like image, text, and audio processing.

## 1. Neural Network Foundations
*   **The Perceptron:** The fundamental building block.
*   **Activation Functions:** Sigmoid, Tanh, ReLU, Leaky ReLU, Softmax.
*   **Architecture:** Input layer, Hidden layers, Output layer (Multilayer Perceptrons/MLP).
*   **Learning Mechanism:** 
    *   Forward Propagation
    *   Loss Functions (Cross-Entropy, MSE)
    *   Backpropagation (Chain rule of calculus)
    *   Optimizers (SGD, Adam, RMSprop)

## 2. Convolutional Neural Networks (CNNs)
Used primarily for Computer Vision (images/video).
*   **Concepts:** Convolutional layers, Filters/Kernels, Pooling (Max/Average), Padding, Stride.
*   **Famous Architectures:** LeNet, AlexNet, VGG, ResNet (Residual blocks to solve vanishing gradient).
*   **Applications:** Image Classification, Object Detection (YOLO, SSD), Image Segmentation (U-Net).

## 3. Recurrent Neural Networks (RNNs)
Used for Sequence Data (Time-series, text, speech).
*   **Concepts:** Hidden state, dealing with sequential input.
*   **Problems:** Vanishing/Exploding gradients over long sequences.
*   **Advanced Architectures:** LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) which use gates to remember/forget information.

## 4. Frameworks
*   **TensorFlow / Keras** (Google)
*   **PyTorch** (Meta - Industry standard for research and increasingly production)
