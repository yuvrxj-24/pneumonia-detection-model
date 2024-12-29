# pneumonia-detection-model
This project focuses on building an Explainable Medical Diagnosis System for classifying pneumonia severity using chest X-ray images. The system aims to assist healthcare professionals by providing accurate predictions and transparent explanations of the results.
In this project, we compared Convolutional Neural Networks (CNN) with traditional machine learning models like Random Forest (RF), Support Vector Machine (SVM), and K-Nearest Neighbors (KNN) for classifying chest X-ray images into NORMAL and PNEUMONIA categories.

CNN: Achieved superior performance by leveraging automatic feature extraction from raw images, capturing spatial hierarchies and patterns crucial for medical imaging.
Traditional ML (RF, SVM, KNN): Required manual feature engineering (e.g., texture or intensity-based features) but showed competitive results on smaller datasets. These models are interpretable but lack the ability to generalize from raw pixel data effectively.
The results emphasize that CNNs excel in image-based tasks due to their end-to-end learning capabilities, while traditional models serve as robust baselines when combined with strong feature engineering.
DATASET link : https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels
