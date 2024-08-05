# Early-Detection-of-Alzheimer-s-Disease-Using-Deep-Learning

# Project Overview
This project aims to leverage deep learning techniques for the early detection of Alzheimer's disease using MRI images. By employing state-of-the-art convolutional neural network (CNN) architectures, we aim to classify the disease into various stages: Non-Demented, Very Mild Demented, Mild Demented, and Moderate Demented. The project explores the effectiveness of models like VGG16, DenseNet, and Inception V3, and addresses the challenge of class imbalance using the SMOTE technique.

# Dataset
The dataset used for this project is the Alzheimer's Dataset from Kaggle, which consists of MRI images categorized into four classes: Non-Demented, Very Mild Demented, Mild Demented, and Moderate Demented.

# Experiments
Experiment 1: VGG16 with Data Augmentation
Objective: Train the VGG16 model with data augmentation to enhance robustness.
Techniques: Rescaling, rotation, zoom, horizontal and vertical flips.
Results: Achieved an AUC of 87.28% on the validation set.
Experiment 2: DenseNet with Data Augmentation
Objective: Evaluate DenseNet's performance with augmented data.
Techniques: Similar data augmentation techniques as VGG16.
Results: DenseNet achieved an AUC of 89.56%.
Experiment 3: Inception V3 with SMOTE
Objective: Address class imbalance using SMOTE and evaluate Inception V3.
Techniques: Synthetic Minority Over-sampling Technique (SMOTE) for balancing classes.
Results: Inception V3 attained an accuracy of 96.84%.

# Results
The models were evaluated based on AUC, accuracy, confusion matrices, and classification reports. The integration of data augmentation and SMOTE techniques significantly improved the models' performance and generalization capabilities.

# Accomplishments
Successfully applied deep learning techniques for early Alzheimer's detection.
Improved model robustness and performance with data augmentation.
Effectively addressed class imbalance with the SMOTE technique.
Achieved high AUC and accuracy across multiple CNN architectures.
