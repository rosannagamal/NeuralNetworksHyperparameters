# Neural Networks Hyperparameters
This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset, which consists of 60,000 32x32 color images across 10 categories (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck). The model architecture includes multiple convolutional and pooling layers, followed by dropout and a dense softmax layer for classification. The goal is to explore model performance under different optimization strategies and learning conditions, achieving up to ~74% accuracy on the test dataset.

**Key steps include:**

- Data loading, visualization, and preprocessing (normalization and one-hot encoding)
- Construction of a CNN with Conv2D, MaxPooling2D, Dropout, and Dense layers
- Model training with early stopping to avoid overfitting
- Evaluation and plotting of training/validation accuracy
- Comparison of multiple optimizers (SGD, RMSProp, Adam) across various learning rates
