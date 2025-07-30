# 🌿 Medicinal Plant Identification using Deep Learning (Present)

This repository presents our research and implementation of a **multi-organ medicinal plant classification system** using advanced deep learning techniques. We explore the visual characteristics of **leaf, bark, stem, and flower** parts of medicinal plants to build a high-accuracy recognition system.

## 📌 Project Objectives

- Perform **feature analysis** across different plant organs (Leaf, Bark, Stem, Flower).
- Evaluate multiple **deep learning models** including CNNs and Transformer-based architectures.
- Implement **hybrid CNN + Transformer** models for performance benchmarking.
- Apply **transfer learning** using pre-trained models to enhance generalization and reduce training time.
- Achieve classification accuracy of **>93%** on a large-scale medicinal plant dataset.

---

## 🧠 Models Used

We benchmark and compare the following models:

- 🔹 **CNN Architectures**  
  - ResNet50, DenseNet121, EfficientNet-B0  
- 🔹 **Transformer-based Models**  
  - Vision Transformer (ViT), Swin Transformer  
- 🔹 **Hybrid Models**  
  - CNN + Transformer Fusion architectures  
- 🔹 **Transfer Learning**  
  - Fine-tuned pre-trained models from ImageNet on plant dataset  

---

## 📊 Dataset

- 📁 Source: **PlantCLEF 2024 Dataset** (subset of 100 medicinal plant species)
- 🔬 Components: Images of **leaf, bark, stem, and flower**
- 🧹 Preprocessing:
  - Resizing and normalization
  - Augmentation (rotation, flipping, zooming)
  - Class balancing

> 💾 Dataset is hosted on **Google Drive** (available upon request)

---

## 🧪 Evaluation Metrics

We use the following metrics to evaluate model performance:

- ✅ Accuracy  
- 📉 Loss  
- 🧮 Precision, Recall, F1-Score  
- 📊 Confusion Matrix  
- 🌈 Grad-CAM visualizations for explainability

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/medicinal-plant-classification.git
cd medicinal-plant-classification
pip install -r requirements.txt
