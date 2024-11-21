
Diabetic Retinopathy Detection

Project Overview
Diabetic Retinopathy (DR) is one of the leading causes of blindness worldwide. Early detection is crucial for effective treatment. This project implements a deep learning model using the VGG16 architecture combined with an Attention Mechanism to classify retinal images into different stages of DR severity.

Model Highlights
The model leverages transfer learning and advanced techniques for enhanced performance:

VGG16 Backbone: A pre-trained convolutional neural network for robust feature extraction.
 
  >Multi-Head Attention: Focuses on significant areas of the retina for better classification accuracy.
  >Gaussian Noise Layers: Improves robustness against variations in input data.
  >Batch Normalization and Dropout: Ensures stable training and prevents overfitting.
    
Features

  >Input Shape: 224x224x3 (RGB images).
  >Multi-Class Classification: Detects stages of DR, from mild to severe.
  >Transfer Learning: Utilizes pre-trained weights from ImageNet for faster convergence.

Dataset
The model was trained on Kaggle.
