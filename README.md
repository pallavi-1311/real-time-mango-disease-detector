# Real-Time Detection of Mango Leaf Diseases

This project presents a deep learning-based approach for identifying diseases in mango leaves using the EfficientNetB0 Convolutional Neural Network. It is aimed at improving agricultural outcomes by enabling early detection of diseases such as anthracnose and rust, which affect mango yield and crop health.

# Project Objective
To develop an automated, real-time disease detection system that can classify healthy and diseased mango leaves using CNN-based transfer learning, improving decision-making for farmers.

# Key Features
- Trained on both Kaggle datasets and real-time field images
- Uses transfer learning with EfficientNetB0 for feature extraction
- Achieved 92.7% training accuracy, 89.04% validation accuracy, and 84.76% test accuracy
- Preprocessing includes contrast/brightness enhancement and resizing
- Includes advanced data augmentation: rotation, flip, zoom, brightness, and contrast
- Tested with Decision Tree, Random Forest, MobileNet for comparison

# Model Architecture
- **EfficientNetB0** (frozen layers) for feature extraction
- **GlobalAveragePooling** for dimensionality reduction
- **Dropout (0.5)** for regularization
- **Dense layer with Softmax** for classification into 3 classes

# Technologies Used
- Python
- TensorFlow / Keras
- EfficientNetB0 (Transfer Learning)
- OpenCV
- Matplotlib

# Dataset
- Mango leaf disease dataset from **Kaggle**
- Real-time images taken manually under field conditions

# Future Improvements
- Improve multi-class accuracy for visually similar diseases
- Use attention mechanisms or ensemble models
- Expand training dataset with more diverse real-field data





