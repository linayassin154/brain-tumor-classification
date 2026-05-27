# Brain Tumor Classification

Deep learning project for multi-class brain MRI classification using custom FFNN and CNN models built with PyTorch.

**Dataset:** [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

Classes:
- Glioma
- Meningioma
- Pituitary
- No Tumor

---

## What This Project Includes

### Dataset & EDA
- Data quality and class balance checks
- Sample image visualization
- Pixel intensity analysis before and after preprocessing

### Preprocessing
- Brain region cropping using contour detection
- Grayscale conversion
- CLAHE contrast enhancement
- Resize to 128×128
- Normalization to [0, 1]
- Data augmentation using NumPy and OpenCV

---

## Models

### FFNN
Custom feedforward neural network with:
- Configurable hidden layers
- Batch normalization
- Dropout
- Gradient clipping
- Activation function experiments

### CNN
Custom convolutional neural network with:
- Multiple convolution blocks
- BatchNorm and Dropout
- Configurable kernels and pooling
- Architecture optimization experiments

---

## Regularization Experiments
- L1 and L2 regularization
- Weight decay tuning
- Overfitting analysis across both models

---

## Final Analysis
- CNN vs FFNN comparison
- Learning curves and evaluation metrics
- Training and inference speed comparison
- Exported experiment results and logs

---

## Tech Stack
Python, PyTorch, OpenCV, NumPy, Matplotlib, scikit-learn
