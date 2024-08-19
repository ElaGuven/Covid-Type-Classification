COVID-19 Chest X-ray Classification
This repository contains the code and report for a project focused on classifying COVID-19 cases using chest X-ray images through deep learning techniques. 

Project Overview
The aim of this project is to develop a Convolutional Neural Network (CNN) to automatically classify chest X-ray images into one of four categories, including COVID-19. The dataset used consists of 6500 chest X-ray images divided into four classes. The project involves several steps, from data preprocessing to model training and evaluation, including efforts to handle imbalanced data and improve model performance through various techniques.

Project Files
Covid Type Classification.ipynb: This Jupyter Notebook contains the code for the entire project, including data loading, preprocessing, model building, training, evaluation, and visualizations.
Multi-Class Classification Report.pdf: This report provides a detailed explanation of the methodologies used, the results obtained, and a discussion of the challenges faced during the project, particularly the issue of class imbalance.
Key Features
Baseline Model:

A CNN model built using Keras, consisting of convolutional, max-pooling, dense, and output layers with softmax activation.
Trained with a dataset split into training, validation, and test sets.
The model was evaluated using accuracy and loss metrics, as well as ROC curves and confusion matrices.
Model Improvements:

Techniques like L2 regularization, dropout, and data augmentation were applied to address overfitting and improve model robustness.
Despite these efforts, the model faced challenges in accurately classifying the minority COVID-19 class due to dataset imbalance.
Transfer Learning:

A VGG16 pre-trained model was applied to further improve performance.
This model showed the best results among the three approaches, particularly in identifying certain classes, though challenges remained with COVID-19 classification.

Results
The baseline model showed issues with overfitting and had difficulty accurately classifying COVID-19 cases.
The improved model reduced overfitting but still struggled with classifying COVID-19 correctly.
The transfer learning model provided the best performance but highlighted the limitations imposed by the imbalanced dataset.

Conclusions
The project demonstrates the potential of CNNs in medical image classification, particularly for COVID-19 diagnosis. 
However, it also underscores the importance of addressing data imbalance and exploring advanced techniques to improve model performance in such challenging tasks.

