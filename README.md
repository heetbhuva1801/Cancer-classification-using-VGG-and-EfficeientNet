# Multi-Cancer Classification using VGG and EfficientNet

This project aims to develop a deep learning-based multi-cancer classification system capable of detecting the presence or absence of various cancer types from medical images. It compares the performance of two popular CNN architectures—**VGG** and **EfficientNet**—and provides a Flask-based web application for real-time cancer detection.

## 🧠 Cancer Types Covered
- Brain Cancer (Glioma, Meningioma, Pituitary Tumor)
- Breast Cancer (Benign, Malignant)
- Cervical Cancer (Various cell types)
- Kidney Cancer (Normal, Tumor)
- Lung and Colon Cancer (Multiple categories)
- Lymphoma (CLL, FL, MCL)
- Oral Cancer (Normal, OSCC)

## 🧰 Technologies Used
- Python 3.8+
- TensorFlow & Keras
- OpenCV, NumPy, Pandas
- Matplotlib, Seaborn
- Flask (for deployment)
- SHAP (for explainability)

## 🚀 Features
- **Multi-class classification** of 8 different cancer types.
- Comparison of **VGG and EfficientNet** architectures with performance metrics.
- **Web interface** using Flask for real-time image upload and prediction.
- Integration of **explainable AI (SHAP)** to interpret model decisions.
- Performance metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.

## 📈 Results
- **VGG Model Accuracy:** ~94%
- **EfficientNet Model Accuracy:** ~91%
- VGG provided better generalization and classification accuracy across datasets.

## 🛠 How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/multi-cancer-classification.git
   cd multi-cancer-classification
