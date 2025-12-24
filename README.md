Casting Product Defect Detection Using Deep Learning
📌 Project Overview

This project focuses on developing an automated image-based defect detection system for casting products using deep learning. The system classifies casting images into defective and non-defective categories, enabling efficient quality inspection and sorting in manufacturing environments. By leveraging Convolutional Neural Networks (CNNs), the model learns spatial and texture-based features associated with real-world casting defects.

🎯 Objectives

Automate quality inspection of casting products

Reduce manual inspection effort and human error

Improve defect detection accuracy and production efficiency

Enable scalable and real-time inspection using computer vision

🧠 Methodology

Data Collection

Industrial casting images labeled as defective or non-defective

Dataset split into training, validation, and testing sets

Data Preprocessing & Augmentation

Image resizing to 200×200 pixels

Pixel normalization (0–1 range)

Data augmentation (rotation, flipping, zoom, translation)

Model Architecture

Convolutional Neural Network (CNN)

Convolution + ReLU activation layers

Max-pooling layers for dimensionality reduction

Fully connected layers with Softmax output

Training & Evaluation

Loss function: Categorical Cross-Entropy

Optimizer: Adam

Evaluation metric: Accuracy

Batch-based training across multiple epochs

🛠 Tech Stack

Programming Language: Python

Deep Learning Framework: TensorFlow / Keras

Image Processing: OpenCV

Data Handling: NumPy, Pandas

Visualization: Matplotlib

Development Environment: Linux / Jupyter Notebook

📊 Results

The trained CNN model effectively distinguishes defective from non-defective casting products

Data augmentation and normalization improve generalization and reduce overfitting

Suitable for integration into real-world quality inspection pipelines

🚀 Future Enhancements

Extend to multi-class defect classification

Implement YOLO-based object detection for defect localization

Deploy as a real-time inspection system

Optimize for edge devices and industrial cameras
