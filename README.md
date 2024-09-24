# Glaucoma Detection System Using Deep Learning

This project implements a glaucoma detection system utilizing retinal fundus images. The system applies advanced deep learning techniques for the segmentation and classification of glaucoma, aiming to provide a reliable diagnostic tool. The project achieves high accuracy by using U-Net for optic disc segmentation and a pretrained GC-Net model for classification. The system is designed to be deployed for practical use, allowing early diagnosis of glaucoma.

## Features

- **Segmentation**: U-Net architecture for automatic optic disc segmentation.
- **Classification**: GC-Net model for classifying retinal fundus images as glaucomatous or normal.
- **Deployment**: A GUI-based system for easy usability by non-technical personnel.

## Libraries Used

The following libraries were used to develop this project:

- **TensorFlow**: For building and training the deep learning models.
- **Keras**: High-level neural networks API used with TensorFlow.
- **OpenCV**: For image processing tasks, such as resizing and transforming images.
- **Matplotlib**: For plotting graphs and visualizing the results.
- **Tkinter**: For developing the graphical user interface (GUI).

## Datasets

The system uses two publicly available retinal fundus image datasets:

- **ACRIMA**: Contains 705 images, with 396 labeled as glaucomatous and 309 as normal.
- **RIM-ONE v3**: Contains 159 images, with 85 healthy and 74 glaucomatous images, providing ground truth for segmentation.

## Results

The system achieved high performance in both training and testing, with the following metrics:
- **Training Accuracy**: 96%
- **Testing Accuracy**: 93%
- **F1 Score**: 0.93
- **Specificity**: 0.95
- **Sensitivity**: 0.92
- **ROC AUC Score**: 0.93
