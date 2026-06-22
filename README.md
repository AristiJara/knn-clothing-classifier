# KNN Classifiers, Image Transformations, and Manipulation
**Authors:** Aristides Jaramillo & Diego Ossa

Image classification project using K-Nearest Neighbors (KNN) applied to a custom clothing dataset. The project covers the full pipeline: image acquisition, dataset creation, feature extraction, and model training using both raw pixel descriptors and HOG (Histogram of Oriented Gradients) descriptors.

---

## About the project

KNN is a supervised learning algorithm that classifies new samples based on the majority class among its k nearest neighbors in the feature space. This project applies KNN to classify clothing images across 4 categories.

### Dataset

**Clothing Dataset Small** — Custom image dataset with 4 categories: hats, pants, shirts, and shoes, in 28×28 grayscale images stored in Google Drive.

---

## Experiments

### Image Acquisition & Dataset Creation
Raw images were collected, transformed, and organized into class folders. Preprocessing steps include grayscale conversion and resizing to 28×28 pixels.

### KNN with Raw Pixel Descriptors
Images are flattened into 1D arrays and used directly as feature vectors. The dataset is split into training, validation, and test sets, and KNN models are evaluated on classification accuracy.

### KNN with HOG Descriptors
HOG (Histogram of Oriented Gradients) features are extracted from each image and used as descriptors, capturing shape and edge information for improved classification performance.

---

## Technologies

- Python
- OpenCV
- NumPy / Matplotlib
- Google Colab / Google Drive

---

## References

[1] Fernández Millán. *OpenCV4 with Python.* 

[2] Gonzalez, R. C., & Woods, R. E. (2017). *Digital Image Processing.*
