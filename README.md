# Brain Tumor Detection Using Deep Learning from MRI Images

This project implements a high-performance diagnostic pipeline for the automated classification of brain tumors using Magnetic Resonance Imaging (MRI). By benchmarking five distinct neural network architectures, the study evaluates the effectiveness of Transfer Learning, Residual Learning, and Hybrid Spatial-Sequential modeling in a clinical context.

## 🚀 Overview

Early and accurate identification of brain tumors is critical for treatment planning. This repository provides a comprehensive comparison of deep learning models categorized into four classes:

* **Glioma**
* **Meningioma**
* **Pituitary Tumor**
* **No Tumor**

## 🧠 Architectures & Frameworks

The project explores a diverse suite of architectures to balance diagnostic sensitivity with computational efficiency:

| Model | Category | Key Feature | Accuracy |
| --- | --- | --- | --- |
| **ResNet50** | Computer Vision | Residual Learning / Skip Connections | **0.98** |
| **VGG16** | Computer Vision | Classical Deep Hierarchical Features | 0.96 |
| **MobileNetV2** | Computer Vision | Depthwise Separable Convolutions | 0.96 |
| **U-Net** | Computer Vision | Spatial Context Preservation (Encoder) | 0.96 |
| **CNN + LSTM** | Deep Learning | Spatial-Sequential Hybrid Modeling | 0.96 |

## 🛠️ Key Features

* **Dataset:** Analysis of 7,023 MRI images (5,712 Training, 1,311 Testing).
* **Preprocessing:** Standardized pipeline including geometric resizing (), intensity normalization, and real-time data augmentation.
* **Interpretability:** Implementation of **Captum** attribution mapping to visualize model "attention" and ensure clinical grounding.
* **Comparative Metrics:** Evaluation based on Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.

## 📂 Project Structure

* `Building_a_Brain_Tumor_Detection_Using_Deep_Learning.ipynb`: The primary implementation notebook including training and evaluation logic.
* `Brain Tumor Detection Using Deep Learning.pdf`: The complete technical research report.

## 📈 Results

The experimental findings indicate that **ResNet50** is the superior architecture for medical precision. However, **MobileNetV2** and the **U-Net Encoder** offer nearly identical accuracy with significantly lower computational costs, making them ideal for deployment on standard medical hardware.

## 🛠 Installation & Usage

1. Clone the repository:
```bash
git clone https://github.com/Iam-Taki/Brain-Tumor-Detection-Using-Deep-Learning.git

```


2. Install dependencies:
```bash
pip install tensorflow numpy matplotlib pillow captum scikit-learn

```


3. Open the `.ipynb` file in Google Colab or Jupyter Notebook to run the training pipeline.

## 🎓 Academic Context

This project was developed for the **Machine Learning & Deep Learning** and **Computer Vision & Deep Learning** courses at the **University of Verona**.

**Author:** Abdullah Al Noman Taki
**Matricola:** VR528988
