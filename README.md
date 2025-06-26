![E-Waste Classifier Banner](banner.png)
![App Preview](preview.gif)
# ♻️ E-Waste Image Classification using EfficientNetV2B0 (Transfer Learning)

This project uses **EfficientNetV2B0**, a powerful deep learning model, to automatically classify electronic waste (e-waste) images into 10 distinct categories. It supports automation in recycling by replacing manual, error-prone sorting with an AI-powered solution.

[![Hugging Face Space](https://img.shields.io/badge/Gradio-Live%20Demo-blue?logo=huggingface)](https://huggingface.co/spaces/Shivamjha09/e-waste-classifier)

---

## 🔍 Problem Statement

E-waste is one of the fastest-growing waste streams globally. Accurate and automated categorization of e-waste is crucial for:
- Efficient recycling
- Safe disposal
- Reducing environmental harm

---

## 🎯 Project Goal

> **To build an AI-powered image classifier that can detect and label e-waste items using a pre-trained EfficientNetV2B0 model with transfer learning.**

---

## 📂 Dataset

The dataset includes 10 categories of e-waste:

- 📱 Mobile
- 🔋 Battery
- 🖨️ Printer
- 📺 Television
- 🖱️ Mouse
- ⌨️ Keyboard
- 🧼 Washing Machine
- 🔊 Player
- 🔌 PCB
- 🔥 Microwave

Each class contains multiple labeled images used for training, validation, and testing.

---

## 🧠 Model Architecture

- ✅ **Base Model**: `EfficientNetV2B0` (pre-trained on ImageNet)
- ✅ **Input Size**: 128x128 RGB images
- ✅ **Layers Added**:
  - Data Augmentation
  - Global Average Pooling
  - Dropout
  - Dense Softmax layer for 10-class output

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| **TensorFlow** | Deep learning framework |
| **Keras** | Model building and training |
| **Gradio** | Web interface for model deployment |
| **Hugging Face Spaces** | Hosting the live app |
| **Matplotlib / Seaborn** | Visualizations |
| **Scikit-learn** | Evaluation metrics |

---

## 📊 Evaluation Metrics

| Metric | Value |
|--------|-------|
| ✅ Test Accuracy | ~94% |
| ✅ Confusion Matrix | ✔️ Plotted |
| ✅ Classification Report | ✔️ Generated |
| ✅ Visual Predictions | ✔️ Shown with true vs predicted labels |

---

## 🧪 Try It Out!

🎯 **Live Demo** (Gradio App):  
👉 [Click here to test the model](https://huggingface.co/spaces/Shivamjha09/e-waste-classifier)

You can upload an image of an e-waste item and get real-time predictions with confidence scores.

---

## 🚀 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/your-username/e-waste-classifier.git
cd e-waste-classifier
