# 🧠 Dog Breed Classification Using Quantum Convolutional Neural Networks (QCNNs)

## 📌 Project Overview

This project explores the application of **Quantum Convolutional Neural Networks (QCNNs)** for classifying dog breeds using the **ImageNet (ILSVRC2012)** dataset. It aims to demonstrate the potential and limitations of quantum computing in the field of image classification, particularly through hybrid quantum-classical approaches.

### 🐶 Dog Breeds Used:

- German Shepherd
- Border Terrier
- Briard
- English Foxhound
- Ibizan Hound

## 📂 Project Details

- **Dataset**: ILSVRC2012 (ImageNet) subset with directories:
  - `German_Shepherd_dir`
  - `Border_Terrier_dir`
  - `Briard_dir`
  - `English_Foxhound_dir`
  - `Ibizan_Hound_dir`

- **Model Accuracy**:  
  Achieved a training accuracy of **27.35%** — relatively low due to the limitations of quantum processing on classical hardware. However, the insights gained from building a hybrid QCNN were significant.

- **Tools & Libraries**:
  - **Quantum Framework**: Qiskit
  - **Machine Learning**: TensorFlow, Keras
  - **Preprocessing**: OpenCV, NumPy

## 📁 Files Included

- `qcnn_dog_breed_classification.py` — Main Python script for model implementation.
- `qcnn_dog_breed_classification.html` — HTML export of training results and architecture.
- `images/` — Folder (not included here) with ImageNet dog breed categories used for training and validation.

> 📥 Download dataset: [ImageNet ILSVRC2012](https://www.image-net.org/)

## ⚙️ Installation & Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/qcnn-dog-breed-classification.git
   cd qcnn-dog-breed-classification
