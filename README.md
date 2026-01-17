
<img width="511" height="768" alt="Screenshot 2026-01-17 150053" src="https://github.com/user-attachments/assets/e0840e81-bb9e-4c3d-afb3-525390acd4fb" />

<p align="center">
  <img src="https://img.shields.io/badge/Rice%20Leaf%20Disease%20Prediction-Deep%20Learning%20Project-green?style=for-the-badge&logo=python&logoColor=white" />
</p>
<p align="center">
  <b>Deep Learning • Convolutional Neural Networks • Image Processing • Data Augmentation • TensorFlow • Keras • OpenCV</b>
</p>


"""
🌾 CNN-Based Rice Leaf Disease Identification

📌 Project Overview
This project focuses on identifying and classifying rice leaf diseases using
Deep Learning (Convolutional Neural Networks) applied to image data.
The objective is to automate disease detection in rice crops, enabling early
diagnosis, reduced crop loss, and improved agricultural productivity through
computer vision.

🎯 Objectives
- Perform image-based data exploration to understand disease patterns
- Preprocess rice leaf images for deep learning models
- Apply image augmentation to address limited dataset size
- Design and train a CNN-based image classification model
- Evaluate model performance for multi-class disease classification

📂 Dataset
Source: Rice Leaf Image Dataset
Type: Image Classification (Agricultural Analytics)

Data Includes:
- Rice leaf images with visible disease symptoms
- 3 disease classes:
    1. Bacterial Leaf Blight
    2. Brown Spot
    3. Leaf Smut

🛠️ Tools & Technologies
Programming Language:
- Python

Deep Learning Frameworks & Libraries:
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV (image handling)

🔍 Exploratory Data Analysis (EDA)
- Visual inspection of rice leaf images across disease classes
- Analysis of class distribution to identify imbalance
- Examination of image resolution and color patterns
- Identification of the need for augmentation to improve generalization

⚙️ Data Preprocessing
- Resized all images to 300 × 300 pixels
- Normalized pixel values for stable training
- Encoded class labels for multi-class classification
- Applied image augmentation techniques:
    - Rotation
    - Zoom
    - Horizontal Flip
    - Brightness adjustment

🤖 Model Used
Convolutional Neural Network (CNN)
- Conv2D layers for feature extraction
- MaxPooling layers for dimensionality reduction
- Dropout layers to reduce overfitting
- Dense layers for final classification
- Softmax activation for multi-class output

📊 Model Evaluation Metrics
- Training vs Validation Accuracy
- Training vs Validation Loss
- Classification performance across all 3 disease classes

✅ Final Model Outcome
- Successfully classified rice leaf images into 3 disease categories
- Image augmentation significantly improved model generalization
- Model demonstrated strong performance on unseen validation data

📌 Conclusion
A complete end-to-end deep learning image classification pipeline was implemented
for rice leaf disease identification. The CNN model effectively learned visual
disease patterns, proving the potential of AI-driven solutions in precision
agriculture and smart farming.

👤 Author:
Aniket Jain
Data Analyst | Machine Learning & Deep Learning Enthusiast
"""
